# URL Generator

## Intro
This tool was created for a client who needed to run a social network campaign. They required links to direct users to their store with specific filters applied. Since filters could vary from campaign to campaign, I came up with the idea of creating a URL generator for that specific website.

Then, the idea of having some kind of template for a situation like that became tempting, even though it would never happened again.

## Instructions
1- You need to add your filters (inside 'wrapper-options') in the following structure:

```
<div id="yourCategory" class="options-group">
	<p class="category-title">yourCategory</p>
	<label>
		<input type="checkbox" name="yourCategory" value="yourValue">
		yourValue
	</label>
</div>
```

Replace `yourCategory` with your actual category name and `yourValue` with your option value and name.

2- Change ``const url = `https://domain.com/products/?view_type=list`;`` with your url.

3- Send the url-generator.html file to the client or upload it to a server. Open it on a browser and start generating!

**Note**: Feel free to change the url-generator.html file name.