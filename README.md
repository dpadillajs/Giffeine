1. **Hit the GIPHY API**.

   - Fool around with the GIPHY API. [Giphy API](https://developers.giphy.com/docs/).
   - Be sure to read about these GIPHY parameters (hint, hint):
     - `q`
     - `limit`
     - `rating`
   - Make sure you switch the protocol in the query URL from **`http to https`**, or the app may not work properly when deployed to Github Pages.

### Instructions

3. When the user clicks on a button, the page should grab 10 static, non-animated gif images from the GIPHY API and place them on the page.

4. When the user clicks one of the still GIPHY images, the gif should animate. If the user clicks the gif again, it should stop playing.

<!-- 5. Under every gif, display its rating (PG, G, so on).

   - This data is provided by the GIPHY API.
   - Only once you get images displaying with button presses should you move on to the next step. -->

### Bonus Goals

1. Ensure your app is fully mobile responsive.

2. Allow users to request additional gifs to be added to the page.

   - Each request should ADD 10 gifs to the page, NOT overwrite the existing gifs.

3. List additional metadata (title, tags, etc) for each gif in a clean and readable format.

4. Include a 1-click download button for each gif, this should work across device types.

5. Integrate this search with additional APIs such as OMDB, or Bands in Town. Be creative and build something you are proud to showcase in your portfolio

6. Allow users to add their favorite gifs to a `favorites` section.
   - This should persist even when they select or add a new topic.
   - If you are looking for a major challenge, look into making this section persist even when the page is reloaded(via localStorage or cookies).
