##### Release 3.1 🚧 WORK IN PROGRESS 🚧

The "Hoodland Open Source Projects" are being split into their individual components and put into the Maven Central Repository.
Testing for this release was done against Linux Mint 22.1 and Windows 11.

---
# Toolbox

**An assorted miscellany of tools and toys.**

- Matrixfile - Easily creates and manages files of CSV data (you may use tabs or other delimiters as you wish).
- QuantumTextFile - Readies a text output file but does not actually create it until and unless the first write operation takes place.
- StatusCodeDescription - Useful for matching HTTP Status Code values to anappropriate text description, as well as determining if the code if passing or valid.
- SubnameFactory - Do you need to programmatically generate several similar names? TestA, TestB, TestC and so on? This makes it easy.
- ZipFileCreator - ...is exactly that. It creates a compressed Zip file containing all files in the directory you specify, recursing down any subdirectories it finds.

- **ToolboxJava** can be found here (TBD) This is a wrapper for Toolbox that allows use as if it were native Java avoiding the usual issues of using compiled Kotlin directly in a Java program.

## Usage & Known Issues
- Clone the repository and open the root directory in IntelliJ IDEA CE.
- The Kotlin code and the overall project is intended for use with IntelliJ IDEA (Community Edition). Eclipse is supported for using the Java wrappers. Feel free to adapt the code to any other IDE or Editor you're comfortable with, with the understanding that I don't officially support such use.
- All projects are "Kotlin First". Use from Java is supported by way of the Java wrappers, and only using the Kotlin bits when a Java wrapping is not available.

## Released under the terms of the MIT License
© 2020, 2021, 2022, 2023 William Hood

*Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished
to do so, subject to the following conditions:*

*The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.*

*THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.*


## Contact Information
https://www.linkedin.com/in/william-a-hood-pdx/

william.arthur.hood@gmail.com
