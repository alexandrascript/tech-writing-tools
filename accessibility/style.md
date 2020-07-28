# Accessibility style guide

Here are some principles to consider when writing for accessible needs.

## Visuals

Review this guide for [designing with screenreaders](https://webaim.org/techniques/screenreader/) and use the [WAVE testing tool](http://wave.webaim.org/).

- Avoid directional instructions and visual language.
   - Readers may not be able to see the layout of a page or the UI, and it is unhelpful to people using screenreaders or an unexpected layout (mobile vs. desktop). Instead of "above", "left", "right", etc, use "earlier", "later", or "following".
   - Avoid referring to UI elements by color, shapes and patterns. Use the element's label whenever possible.
- Spell out acronyms and symbols.
   - Avoid unnecessary abbreviations or acronyms. Spell out words like "and", "plus", "minus", and "about" instead of using their respective symbols.
- Keep it brief and clear.
   - Use shorter words when possible. For example: "more" instead of "additional"; "show" instead of "display"; "buy" instead of "purchase"
   - Refer to [fewer words](../style/fewer-words.md)
- Writing should be scannable.
   - Avoid long paragraphs.
- Key information should go first. Front-load with desired actions.
   - Use bullet points.
   - Use headings to create logical structure.
   - Use nested and consecutive headings.
- Help provide context for screenreaders.
   - Don't have empty headings or headings with no associated content.
- Lead into new page elements.
   - Create expectations for the user. Page elements include tables, lists, images, videos, searches, commands, and code blocks. Always introduce a new page element using a lead-in sentence that explains what information the element contains or what the user needs to do.
- Links should be descriptive. 
   - Avoid "click here" and "learn more" when possible. Links should make sense when read out of context.
   - Use an external link icon to indicate that the link opens in a new window or tab. This can be done by adding `target="_blank"` to your link tag.
   - If the link is for a download, the text should indicate that action in addition to the file type and title. For example: "download the PDF of our style guide"
- Use sensitive language.
   - Instead of “see” or “view”, use “go to” or “open”
- Avoid unnecessary font formatting.
   - Don’t force line breaks (hard returns) within sentences and paragraphs. Line breaks might not work well in resized windows or with enlarged text.

### Images

- Images should be enhancing or adding context to already written content.
   - Images should not be the sole method of communication. 
- Be thoughtful about alt text. 
   - Not every image requires alt text, such as screenshots of the UI.
- Symbols represented in the UI should have alt text which matches the alt text in the UI.
   - Use SVGs when possible.
- SVGs (scalable vector graphics) can be made used for icons, images, logos, etc and scale without any reduction in visual quality.
   - The best way to make SVGs accessible to Assistive Technologies (AT) like screen readers and speech recognition tools is to put it directly into your HTML using the `<svg>` tag. Avoid using `<embed>`, `<object>`, or `<img>` elements when using SVGs.

### Color

- Use high contrast colors for fonts and backgrounds.
   - Black text on a white background is standard for a reason.
- Use an [accessible color palette](http://colorsafe.co/).
   - Be mindful not to pair colors which are commonly problematic for those who are colorblind (i.e. red and green or purple and yellow).

### Video

- Use the [Photosensitive Epilepsy Analysis Tool (PEAT)](https://trace.umd.edu/peat) to make sure your media does not cause seizures.
- Do not auto-play your media. 

### Code snippets

- Always use code tags. 
   - HTML: `<code></code>`
   - Do not use images for code snippets.
   - If the snippet is short or just the name of a function, it can be included inline. For example: `<code>myObject()</code>`.
   - If the code sample is longer, it should be in a separate container. The HTML should look like this:
   ```
   <code>
   # Code sample
   myFunction() {
      var yourCode = goeshere;
   }
   </code>
   ```
   - If using Markdown, [refer to the Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code)

## Audio

### Video

- All videos should have captions.
   - If using [YouTube's auto-caption tool](https://support.google.com/youtube/answer/6373554?hl=en), edit the caption to include punctuation and correct any language that was misheard.
   - Include all text and necessary sound effects.

## Touch

- Consider that not all people will use touch in the same way. 
   - Swiping may not be an option⁠. A user may instead use arrow keys to navigate an application.

## Cognition

### Write inclusive documentation

- Avoid "simple" and "simply".
   - What might be simple for you might not be simple for others.
- Avoid bias and harm when discussing disability and accessibility.
- Use diverse and inclusive examples.
   - Use diverse names, genders, ages, and locations in examples. 
- Avoid vague and confusing references between a pronoun and its antecedent.
   - Not recommended: _If you type text in the field, it doesn't change._
   - Recommended: _If you type text in the field, the text doesn't change._
- Use gender neutral pronouns.
   - Use the singular "they" pronoun unless referring to a person who identifies as a specific gender.
- Avoid disability bias and ableist language.
   - Don't describe people without disabilities as "normal" or "healthy". This contributes to othering and alienation of people with disabilities by implying they are abnormal or sick. Instead, use terms such as: nondisabled person, sighted person, hearing person, person without disabilities, neurotypical person.
- Use race-neutral language. The use of "whitelist" and "blacklist" legitimizes and perpetuates racism. 
   - Instead of "blacklisted," use "blocked" or "blocklist" (in reference to adding an item to a list).
   - Instead of "whitelisted," use "allowed" or "allowlist" (in reference to adding an item to a list).
   - Avoid "native" when possible. Use a more precise term. For example, use "built-in" to describe a feature that's part of a product.
   - Do not use "master"/"slave". Instead, use alternative terms appropriate to your domain. For example, "primary"/"secondary" or "parent"/"child"
   
   
### Write for international audiences

- Use the subject-verb-object sentence structure.
   - While this structure is not used by all languages, it’s widely recognized.
- Avoid ambiguity.
   - Some words and parts of speech may be left out when thinking of American, English-speaking audiences, which will frustrate translation teams. For example:
   - Avoid unclear pronouns.
   - Avoid gerunds.
   - Avoid portmanteaus.
   - Be positive.
- Avoid jargon.
   - Sparate ideas into different sentences/paragraphs/sections, as necessary.
   - Avoid slang and metaphors.
   - Use adjectives sparingly.
- Avoid colloquialisms.
   - Phrases like "ballpark figure," "back burner," or "hang in there" can be confusing.



