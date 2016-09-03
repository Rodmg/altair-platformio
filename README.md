# Altair Development Board support for PlatformIO

## Installing

1. Clone or download this repository

2. If it's your first time using PlatformIO, create a dummy PlatformIO project to make sure that the ``~/.platformio`` folder gets created

3. Create the folder ``~/.platformio/boards`` if it doesn't exist

4. Paste the file ``aquila_boards.json`` inside `~/.platformio/boards/``

5. Paste the ``altair`` folder in ``~/.platformio/packages/framework-arduinoavr/variants/``

6. Now you can create a PlatformIO with the following settings:
  ```
  [env:Altair]
  platform = atmelavr
  framework = arduino
  board = Altair
  ```

**Note:** Repeating step 5 may be needed in case that PlatformIO updates the framework-arduinoavr in the future.
