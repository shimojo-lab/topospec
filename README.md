# topospec

A simple tool to check if the topology of a network conforms to spec.

## Requirements

- Python 2.7.x
- pip
- (virtualenv, direnv, pythonz, etc.)

## Prepare & Run

1. Edit `spec_path` in `topospec.conf` if needed.
2. Install dependencies.

    ```
    $ pip install -r requirements.txt
    ```
3. Launch controller.

    ```
    $ ./tool/run_controller.sh
    ```

## Notes

- Hosts are not detected if they don't emit packets.
