Non-Responsive-Bootstrap
========================

Non responsive version of boostrap

About

Most popular front-end framework Bootstrap’s non responsive version. You can use this framework for developing standart structured web pages. This framework contains all features of boostrap but responsive features.

Actually i don’t work hard for this software. I’m just clean @media queries and add some classes. I just developed this software for practicality. You don’t need to edit Bootstrap anymore. just download the software.

How to use ?

Change hyperlink referance of boostrap.css file with nonresponsive-bootstrap.css 

<link href="css/nonresponsive-bootstrap.css" rel="stylesheet">

You can use grid system just like regular boostrap. It has only one difference. You must add main container (main-cnt-?) as parent of .container calss.

Notice: In this framework col-xs, col-sm, col-md, col-lg classes are the same.

Main Container Classes

.main-cnt-xs = 480px
.main-cnt-sm = 768px
.main-cnt-md = 992px
.main-cnt-lg = 1200px

Example

<div class=”main-cnt-md”>
	<div class=”container”>
		<div class=”row”>
			<div class=”col-md-12”>
			</div>
		</div>
	</div>
</div>

Lisence

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
