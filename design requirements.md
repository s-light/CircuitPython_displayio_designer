# Design Requirements

## Goal
- project environment
    - quasar cli based vue web app that can run on github pages 
    - and also as minimal web-tool to be included easily in other tools
        to be included in 
        - [CircuitPython Code Editor](https://github.com/circuitpython/web-editor))
        - [Browserbasierte Blockly-IDE für CircuitPython](https://github.com/KidsLabDe/makerSpaceOS-Editor) or similar
    - packaged for PyPi so its easily usable locally
- project
    - simple and intuitiv UI
    - no help needed approach
    - drag & drop
    - graphical
    - WYSIWYG
    - maybe Blockly compatible code generation??
        - `Blockly` compatible would mean we could have a nice learning way:
            - first drag drop design what you need
            - dig deeper in the code with Blockly view
            - dig even deeper in real text view
    - working with all screens / displays
        - configurable 
            - screen size
            - controller type
            - connection way
            - color mode
        - with search for common available / used screens
            - must include all adafruit sold displays with links to product pages and learn guides
            - include all compatible and supported waveshare products
            - must include all boards with attached screens
    - accurate preview mode
    - support touch
    - include / support all available (adafruit official and community bundle) displayio extensions libraries
    - follows best practice from adafruit examples
    - generates
        - CircuitPython code `display.py` that is very easy to include / use from the code.py file. (also generates an example code.py)
        - [circuitpython_display_layouts](https://github.com/FoamyGuy/circuitpython_display_layouts) (if this makes sense.)

