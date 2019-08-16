# Date Range Picker

![Improvely.com](https://i.imgur.com/UTRlaar.png)

This date range picker component creates a dropdown menu from which a user can
select a range of dates. I created it while building the UI for [Improvely](http://www.improvely.com), 
which needed a way to select date ranges for reports.

Features include limiting the selectable date range, localizable strings and date formats,
a single date picker mode, a time picker, and predefined date ranges.

## [Documentation and Live Usage Examples](http://www.daterangepicker.com)

## [See It In a Live Application](https://awio.iljmp.com/5/drpdemogh)

An extension of [dangrossman's daterangepicker](https://github.com/dangrossman/daterangepicker), with support for configuring following additional properties/events.

## Additional Custom Properties

<table width="100%">
	<tr>
		<th valign="top" colspan="3" align="left"><a href="#props" name="props">Properties</a></th>
	</tr>
	<tr>
		<th valign="top" width="120px" align="left">Property</th>
		<th valign="top" align="left">Description</th>
		<th valign="top" width="60px" align="left">Type</th>
		<th valign="top" width="60px" align="left">Default</th>
	</tr>
	<tr>
		<td valign="top"><code>interval</code></td>
		<td valign="top">
			A string Represeting which interval selection to use for date range picker, when weekly only full weeks are allowed for selection, similarly for monthly
		</td>
		<td valign="top"><code>DAILY|WEEKLY|MONTHLY</code></td>
		<td valign="top"><code>DAILY</code></td>
	</tr>
	<tr>
		<td valign="top"><code>ranges</code></td>
		<td valign="top">
			Can be either an object or an array of objects, when an object, its behavior will be same as default daterangepicker,
			when an array, each object can have following properties,
			<code>startDate</code>: start date for range
			<code>endDate</code>: end date for range
			<code>label</code>: label to show for range
			<code>allowInterval</code> Optional; interval only for which this range should be enabled, enabled for all intervals if skipped and for DAILY interval all ranges will be always enabled
		</td>
		<td valign="top"><code>Object|Array</code></td>
		<td valign="top"></td>
	</tr>
</table>

## License

The MIT License (MIT)

Copyright (c) 2012-2019 Dan Grossman

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
