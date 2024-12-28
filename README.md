# URL Generator

## Intro
This tool was created for a client who needed to run a social network campaign. They required links to direct users to their store with specific filters applied. Since filters could vary from one campaign to another, I came up with the idea of creating a URL generator for that specific website.

Then, the idea of having some kind of template for a situation like that became tempting, even though it would never happened again.

## Instructions
1- Open **url-generator.html** file on a code/text editor.

2- Add your filters inside `#wrapper-options` (line 137) using the following structure:

```html
<div id="yourCategory" class="options-group">
	<p class="category-title">yourCategory</p>
	<label>
		<input type="checkbox" name="yourCategory" value="yourValue">
		yourValue
	</label>
</div>
```

Replace `yourCategory` with your actual category name and `yourValue` with your option value and name.

3- In the `generateLink` function, change the `url` variable (line 164) with your actual URL. You can use a URL with predefined parameters; for example:
	
`https://domain.com/products/?view_type=list`

The result will be something like this:

`https://domain.com/products/?view_type=list&foo=true&bar=red`

4- Send the **url-generator.html** file to the client or upload it to a server. Open it on a browser and start generating!

**Note**: Feel free to change the file name to whatever you want.