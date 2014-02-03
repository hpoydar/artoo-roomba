# Commands

## start

Public: Puts roomba in start mode.

Returns nil.

## safe_mode

Public: Puts roomba in safe mode.

Returns nil.

## full_mode

Public: Puts roomba in full mode.

Returns nil.

## forward(seconds, speed=slow) → nil

Public: Moves roomba forward for seconds amount of time at speed (speed(int) between 0 and 500).

- **seconds** - params
- **speed=slow** - params

Returns nil.

## fast_forward(seconds) → nil

Public: Moves roomba forward for seconds amount of time at max speed.

- **seconds** - params

Returns nil.

## stop

Public: Stops the roomba.

Returns nil.

## backwards(seconds) → nil

Public: Moves roomba backwards for seconds amount of time at default speed.

- **seconds** - params

Returns nil.

## nudge_left

Public: Turns roomba a little bit to the left.

Returns nil.

## nudge_right

Public: Turns roomba a little bit to the right.

Returns nil.

## turn_left(seconds=1) → nil

Public: Turns roomba to the left the specefied amount of seconds.

- **seconds** - params

Returns nil.

## turn_right(seconds=1) → nil

Public: Turns roomba to the right the specefied amount of seconds.

- **seconds** - params

Returns nil.

## turn_around

Public: Turns roomba 180 degrees.

Returns nil.

## drive(speed, direction, seconds = 0) → nil

Public: Drives the roomba at speed (from 0 to 500) and direction (straight=32768, clockwise=65535, counterclockwise=1) for the specefied amount of time (seconds).

- **speed** - params
- **direction** - params
- **seconds** - params

Returns nil.

## play(song_number) → nil

Public: Plays the song specified by song_numer.

- **song_number** - params

Returns nil.

## song(notes[Collection], song_number[Integer]) → nil

Public: Stores a song in the roomba.

- **notes[Collection]** - params
- **song_number[Integer]** - params

Returns nil.

## beep

Public: Makes roomba beep.

Returns nil.
