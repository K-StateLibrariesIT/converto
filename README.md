# converto
An all in one web app designed to convert csv files into a portable web code section to be added to web pages.

Currently built for KS document schedules, but can be easily modded for other, similar conversions.
Set up to accept local upload of three csv files. Outputs html with individual csv entries set up in divs as a pseudo-table. The outputted html includes a simple javascript filter with search box built into the html. The rows and columns have consistent classes to make it easy to manipulate them with css. New css can be added externally, or added by changing the contents of the style area near the beginning of the contents of the "firstpart" var (holds a template literal).

The html produced can be dropped right into a web page in a wcms. The css and js is completely self-contained as internal.

Designed to be quick and easy; something that could be emailed to another staff member to allow them to make changes to a page in someone else's wcms without their needing to know anything about how the webcode works. Works out of a web browser, so they don't need access to any additional software or even the shell anywhere.

Copyright 2018, Kansas State University Libraries

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
