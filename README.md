# use-in-on-screen

hook to know if a element is on the screen

```
    import useIsOnScreen from "use-is-on-screen";


    const isInViewport = useIsOnScreen(element);

```

# With REACT ⚛ !!!

```
    import React, { useState, useRef } from "react"
    import useIsOnScreen from "use-is-on-screen";

    function MyComponent() {
        const isInViewport = useIsOnScreen(element);

        const element = useRef(null)

        return (
            <div ref={element}>
                this div {isInViewport ? "is" : "is not"} on screen
            </div>
        )

    }

```

### Parameters

- element could be ref or current (domHTML)
- onlyOnce if only can happen once
- dividend if you want it to come out with a few pixels before based on a parameter to divide the screen


🙌 Good luck out there my friend 🙌