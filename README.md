# Description

Textbox enter widget is a standard Mendix textbox, that will trigger a microflow when the enter button is pressed.

## Typical usage scenario

The widget was initially developed to serve as the input field for a search functionality. Users can enter their query and kick off the microflow that performs the search, using the enter-key.

## Features and limitations

Can trigger microflows synchronously or asynchronously, with or without a loader.
 
## Configuration

Simply add the widget in place of a regular textbox, and apply styling as needed.

The following options can be configured:

- Microflow: The microflow to trigger. Must return boolean, though only the callback matters, not he actual result. A default 'true' return suffices.
- Attribute: The attribute for the textbox. Serves as input string for the microflow.
- Asynchronous: If set to true, the microflow will be triggered as an asynchronous microflow.
- Show progress: If set to true, shows a standard Mendix 'loading' indicator
- Progress message: The message shows in the loading indicator. Not shown if 'show progress' is set to false.

### Known bugs

none at present
