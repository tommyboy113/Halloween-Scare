# Halloween-Scare

import winsound
import time
import random

time1 = 13
time2 = 25

i = 0
while i < 1:
    sound = random.randrange(1,6)
    print(sound)
    if sound == 1:
        winsound.PlaySound('Suicide.wav', winsound.SND_ASYNC)
    
    elif sound == 2:
        winsound.PlaySound('Howl1.wav', winsound.SND_ASYNC)

    elif sound == 3:
        winsound.PlaySound('Cackle3.wav', winsound.SND_ASYNC)
        
    elif sound == 4:
        winsound.PlaySound('demoniclaughter.wav', winsound.SND_ASYNC)
        
    elif sound == 5:
        winsound.PlaySound('nmh_scream1 (1).wav', winsound.SND_ASYNC)
    
    time.sleep(random.randrange(time1, time2))
