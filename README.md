# particleHeader

- [particleHeader](#particleheader)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Example](#example)

## Installation

- Clone this repository into your project folder
  > git clone <https://github.com/sottom/particleHeader.git>

## Usage

- Add link to the particleHeader library in the \<head> tag of your html document

    ```html
    <head>
        <script src="/particleHeader.js"></script>
    </head>
    ```

- Add canvas element to the top of your body

    ```html
    <body>
        <!-- must have id="canvas" -->
        <canvas id="canvas"></canvas>
    ```

- Add call to particleHeader() function immediately before the ending \<\/body> tag
    ```html
        <!-- add path to the image your want to render as a parameter -->
        <script>
            particleHeader('/path/to/image')
        </script>
    </body>
    </html>
    ```

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Particle Header</title>

    <!-- link to particleHeader library -->
    <script src="/particleHeader.js"></script>
</head>
<body>
    <!-- canvas element with id="canvas" -->
    <canvas id="canvas"></canvas>

    <!-- call to particleHeader() function with img path as parameter -->
    <script>
        particleHeader('/img/467-saxophone.png')
    </script>
</body>
</html>
```
