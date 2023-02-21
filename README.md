# Print-Color
This is a Python package that provides a simple and easy-to-use interface for printing colored text in the console. With PrintCor, you can customize the color, background, boldness, italics, and underlining of your text, making it easy to highlight important information or create visually appealing outputs.

Console Text Styling
This is a Python module for styling text in the console with different colors and styles. It allows you to add color and emphasis to your console output, making it easier to read and understand.

Usage
To use the module, simply import it into your Python script:

from console_text_styling import PrintCor
You can then create a PrintCor object and customize its properties to style your text:

print_red = PrintCor(color='red', bold=True, background='black')
print_red.print_text('This text is red')
You can customize the following properties of a PrintCor object:

text: The text to be printed.
color: The color of the text. Available options are black, red, green, yellow, blue, magenta, cyan, and white.
background: The background color of the text. Available options are black, red, green, yellow, blue, magenta, cyan, and white.
bold: Whether the text should be bolded.
underline: Whether the text should be underlined.
italic: Whether the text should be italicized.
You can call the print_text method of a PrintCor object to print the styled text to the console.

Examples
Here are some examples of how to use the PrintCor module:

print_red = PrintCor(color='red', bold=True, background='black')
print_red.print_text('This text is red')

print_yellow = PrintCor(color='yellow')
print_yellow.print_text('This text is yellow')

print_cyan = PrintCor(color='cyan', bold=True, background='black')
print_cyan.print_text('This text is cyan')

print_green = PrintCor(color='green', bold=True, background='black')
print_green.print_text('This text is green')
License

There are some presets included to make easier to call, they are:
pRed('Your Text Here') #print a text with font-color red and bold: true;
pGreen('Your Text Here') #print a text with font-color green and bold: true;
pYellow('Your Text Here') #print a text with font-color yellow and bold: false;
pCyan('Your Text Here') #print a text with font-color cyan and bold: true;

This project is licensed under the MIT License - see the LICENSE file for details.
