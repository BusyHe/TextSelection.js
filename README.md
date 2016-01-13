TextSelection
=============
Library on a pure JavaScript that allowed get or set range positions based on text offset.


    ...
    
    var caretPos = getNodeCaretPosition(document.getElementById('editor'));
    
    ...
    
    setCaretPosition(document.getElementById('editor'), caretPos);
    
    ...
    
    // Set position to the end of text.
    setNodeCaretPosition(document.getElementById('editor'), -1);
    
    ...


Supported browsers
==================
All browsers, except IE < 9.


License
=======
Distributed under MIT License.

