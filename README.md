# apple-shortcuts
Various shortcuts for the Apple Shortcuts app.

## For Obsidian
- [Add to Daily Note](https://www.icloud.com/shortcuts/305c023239b1439886f125bec57afd2e): Parent shortcut that takes text and runs the following shortcuts based on the following conditions:
	- If the text starts with **`- `**, it sends it to [Add to Daily Log](https://www.icloud.com/shortcuts/f880490899104093b02ec13916d0761e), which adds inputted text to the `## Log` area of my daily note.
	- If the text starts with **`/b `**, it sends it to [Add to Slip Box](https://www.icloud.com/shortcuts/417a8d5a182446eb88b419afca0aea70),” which adds inputted text to the bottom of your daily note file.
	- Otherwise, it sends text to [Add to Journal](https://www.icloud.com/shortcuts/f00f4dcfd69b424e869d07ac009883bf), which adds inputted text under the `## Notes` area of my daily note.  
	- If you tap “ok” without writing anything, the shortcut will run [Open Daily Note](https://www.icloud.com/shortcuts/d04de9f3057d4a3bac360521082c6bb1).  

- **Note:** Below, Link to Obsidian, Tweet to Obsidian, and Tweet to Markdown use the [Actions](https://apps.apple.com/us/app/actions/id1586435171) app (iOS + Mac) for retrieving link titles.
- [Link to Obsidian](https://www.icloud.com/shortcuts/a376a2ab4ad643b2a6ccf5b20cc92a54): Takes URLs and formats it as a markdown link (using the page title as the link alias) before sending it to “**Add to Slip Box**”. If the link is a Tweet or Bluesky post, then it instead passes the URL to either “**Tweet to Obsidian**” or “**Skeet to Obsidian,”** respectively.
- [Tweet to Obsidian](https://www.icloud.com/shortcuts/f231761b70ab41b3a1ece6baee87b24e): Takes a Tweet URL, converts it to Markdown using “**Tweet to Markdown**,“ then sends the formatted Tweet to “**Add to Slip Box**”.
	- [Tweet to Markdown](https://www.icloud.com/shortcuts/5ecde07951ea47bf872c668a10ed6ca1): Takes a Tweet URL and outputs it as a [[Markdown]] link followed by a blockquote of the tweet itself. If the tweet has images or a quote tweet in it, then this includes a rendered preview of the tweet after the blockquote.
- [Skeet to Obsidian](https://www.icloud.com/shortcuts/a376a2ab4ad643b2a6ccf5b20cc92a54) does the same as above while using the below shortcut to convert a Bluesky post URL to markdown:
    - [Skeet to Markdown](https://www.icloud.com/shortcuts/3fb36919240f47b0a0ed577a8f9771f1): Uses the [Bluesky API](https://docs.bsky.app/docs/advanced-guides/posts) to achieve the same effect as above except with much greater capability: it can embed images, videos, and quoted posts directly.

## Lifestyle
- [Calculate Tip](https://www.icloud.com/shortcuts/bca824e768c849d3a3bde57f08a15845): Enter a total amount and choose a tip size to get the tip amount and total sum.
- [Send Split Requests](https://www.icloud.com/shortcuts/4e6ac2eb93984133a43668aaec8ef7d2): Enter a total amount and choose contacts. After specifying whether you want to include yourself in the split, the shortcut splits the total evenly and sends Apple Cash requests to everyone.
- [Send Requests to Multiple People](https://www.icloud.com/shortcuts/ccc85c455f3e40e7b2805d294303d071): Enter an fixed amount to request from multiple contacts via Apple Cash.
