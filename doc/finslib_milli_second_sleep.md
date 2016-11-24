# Finslib API Reference

## Functions

### `finslib_milli_second_sleep( int msec );`

#### Parameters

| Parameter | Type | Description |
| :--- | :--- | :--- |
|**`msec`**|`int`|The amount of milliseconds the current thread should be suspended.

#### Returns

| Type | Description |
| :--- | :--- |
|`void`|This function has no return value|

#### Description

The function finslib_milli_second_sleep()` suspends the current thread for the amount of milliseconds specified.
The accuracy of the sleep time depends on the operating system specific implementation and the amount of other
threads and processes which compete for time slots.