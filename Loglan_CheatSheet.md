# Loglan Cheat Sheets #

## Loglan - Template 1 ##

```loglan
/* Initilaize local variables
n = 0
max_frames = 56000

perform CONVERT_LOGS_TO_ARRAYS
perform CHECK_MAX_FRAMES
perform CALCULATIONS
perform CONVERT_ARRAYS_TO_LOGS

end

CONVERT_LOGS_TO_ARRAYS:
dowhile GET_FRAME ()
   n = n + 1
   LOG[n] = LOG_IN
enddo
return

CHECK_MAX_FRAMES:
IF (n > max_frames) THEN
   call DISPLAY_ERROR('Error: Input curves must have at most max_frame samples')
ENDIF
return

CALCULATIONS:
/* One or a combination of the following:
/*     loglan
/*     C++      (begin_c  .... end_c)
/*     matlab 
return

CONVERT_ARRAYS_TO_LOGS:
call REWIND ()
n = 0
dowhile GET_FRAME ()
   n = n + 1
   LOG_OUT = LOG[n]
   call PUT_FRAME ()
enddo
return
```