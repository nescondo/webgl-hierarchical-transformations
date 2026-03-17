# Simple showcase of hierarchical transformations in WebGL.

<ol>
    <li>3 layers of hierarchical transformation within the 2D scene.</li>
    <li>Transformations and key inputs for each object and layer are as follows:</li><ol>
        <li>Layer 1 - face</li>
            <ol>
                <li>Translation</li>
                <ol>
                    <li>Left = 'a'</li>
                    <li>Right = 'd'</li>
                    <li>Up  = 'w'</li>
                    <li>Down = 's'</li>
                </ol>
                <li>Rotation</li>
                <ol>
                    <li>counter-clockwise = 'q'</li>
                    <li>clockwise = 'e</li>
                </ol>
                <li>Scaling</li>
                <ol>
                    <li>Larger = 'z'</li>
                    <li>Smaller = 'x'</li>
                </ol>
            </ol>
        </li>
        <li>Layer 2 - nose</li>
            <ol>
                <li>Translation</li>
                <ol>
                    <li>Up = '3'</li>
                    <li>Down = '4'</li>
                    <li>Right  = '1'</li>
                    <li>Left = '2'</li>
                </ol>
                <li>Rotation</li>
                <ol>
                    <li>counter-clockwise = '5'</li>
                    <li>clockwise = '6</li>
                </ol>
                <li>Scaling</li>
                <ol>
                    <li>Larger = '7'</li>
                    <li>Smaller = '8'</li>
                </ol>
            </ol>
        </li>
        <li>Layer 2 - left eye and right eye</li>
            <ol>
                <li>Translation</li>
                <ol>
                    <li>Right = 'ArrowRight'</li>
                    <li>Left = 'ArrowLeft'</li>
                    <li>Down  = 'ArrowDown'</li>
                    <li>Up = 'ArrowUp'</li>
                </ol>
            </ol>
        </li>
        <li>Layer 3 - left pupil</li>
            <ol>
                <li>Translation</li>
                <ol>
                    <li>Left = 't'</li>
                    <li>Right = 'y'</li>
                    <li>Up  = 'u'</li>
                    <li>Down = 'i'</li>
                </ol>
                <li>Rotation</li>
                <ol>
                    <li>counter-clockwise = 'o'</li>
                    <li>clockwise = 'p'</li>
                </ol>
                <li>Scaling</li>
                <ol>
                    <li>Larger = '['</li>
                    <li>Smaller = ']'</li>
                </ol>
            </ol>
        </li>
        <li>Layer 3 - right pupil</li>
            <ol>
                <li>Translation</li>
                <ol>
                    <li>Left = 'c'</li>
                    <li>Right = 'v'</li>
                    <li>Up  = 'b'</li>
                    <li>Down = 'n'</li>
                </ol>
                <li>Rotation</li>
                <ol>
                    <li>counter-clockwise = 'm'</li>
                    <li>clockwise = ','</li>
                </ol>
                <li>Scaling</li>
                <ol>
                    <li>Larger = '.'</li>
                    <li>Smaller = '/'</li>
                </ol>
            </ol>
        </li>
    </ol>
    <li>Implemented per-vertex color for objects instead of uniform coloring.</li>
</ol>

**Apologies for not being able to input interactions directly on webpage!**
