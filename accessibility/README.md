# Accessibility

The content we create must be accessible and usable for the widest possible audience. This
includes users of all mental and physical capabilities. We must always consider standards for
accessibility and inclusion when editing and creating content, from the words we choose to
the way our content is organized.

I've written an [accessibility style guide](style.md) which outlines some best practcies.
Feel free to copy this document in whole and add it to your company style guide.

I've also included [accessibility in my speaking policy](https://heyawhite.com/speaking/#a11y).

Read the best practices or skip ahead to [resources](#resources).

## Best practices

### 1. Use inclusive language

When considering how to write and speak with inclusive language, there are words we should
use and language to avoid. Language to avoid may sound awkward at best or at worst, be
offensive.

Writing inclusive language in our docs starts with realizing the ways in which we've
internalized ableism in our everyday lives.

- Read [guidelines for writing about people with disabilities](https://adata.org/factsheet/ADANN-writing)
- Avoid [euphamisms](https://aeon.co/essays/euphemisms-are-like-underwear-best-changed-frequently)
- Use precise language. Read a [DEI glossary](https://docs.google.com/spreadsheets/u/1/d/163OyYVe276mhbzsiJ_Ik-yGH_bd2ofgiWEAhwXYoiVA/preview#gid=0)

### 2. Write clear instructions 

Clear instructions are the most critical element of a technical writer's job. We recommend you
write short, complete sentences; use precise language; use exact measurements; and use nouns
instead of pronouns. Additionally, we recommend that you break up longer tasks into smaller
chunks and share examples.

For UI copy, clear instructions mean that the user can always answer 3 questions: where am I?
What can I do here? How do I move forward?

### 3. Reduce visual cues

Don't rely exclusively on the visual elements to convey information. This includes colors, patterns,
images, font styles, and directional language. Always use text or alt text along with visual elements. 

From W3C:

*  Avoid [sensory characteristics](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0&showtechniques=133#qr-content-structure-separation-understanding)
*  [Use color](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0&showtechniques=132%2C133%2C141#use-of-color)
   as one of many elements to communicate

### 4. Create informative and semantic titles / headings

Heading language should be scannable and understood without context. Additionally, it's important to
use semantic HTML, which means the HTML tags you choose correctly align with the value of the content
between the tags.

*  Read the [W3C's semantic HTML guide](https://www.w3schools.com/html/html5_semantic_elements.asp)
*  Take the [Learn Accessibility content structure module](https://web.dev/learn/accessibility/structure/)

### 5. Create meaningful link and alt text

Provide unique, consistent, and relevant labels for link text to allow people who use screen readers
(and those who don't) to take action. 

Alt text ensures all users, regardless of visual ability, can appreciate the image content on your
site. Alt text should be contextual, concise, and spared from too many keywords. If the image is
purely decorative, consider including no alt text to keep from distracting a user with a screen reader.

Want to know how folks experience your content? Test it! [Review W3C's recommended accessbiliity
tools](https://www.w3.org/WAI/people-use-web/tools-techniques/).

### 6. Be clear and concise

Clear, simple text lets your audience focus on learning, rather than deciphering what you're trying
to say. 

## Resources

Here are a list of resources on the topic of accessibility. Some are directly related to writing and
communication, others more loosely connected about web development and design.

### Writing and content

- [A11y Project content style guide](https://www.a11yproject.com/content-style-guide/)
- - [A11y style guide](https://a11y-style-guide.com/style-guide/) for developers, designers, and writing
- Google developer documentation style guide:
  [accessibility](https://developers.google.com/style/accessibility) and
  [inclusive language](https://developers.google.com/style/inclusive-documentation)
- [MailChimp's guide on writing for accessibility](https://styleguide.mailchimp.com/writing-for-accessibility/)

While not primarily about content, the [Learn Accessibility](https://web.dev/learn/accessibility/)
offers useful commentary on business and legal impact, which can be used to
argue for [funding accessibility](https://pleasefunda11y.com/).

### Talks

- ["Clicks Without Limits: Content Design for Everyone, Everywhere"](https://youtu.be/af1zgx1RXHs?feature=shared), a talk by Eric Zrinsky
- ["A11y friendly documentation"](https://github.com/carolstran/tech-talks/blob/master/abstracts/a11y-friendly-docs.md),
  a talk by Carolyn Stransky ([video from Write The Docs](https://youtu.be/SLUJG625Si0))
- ["Don't say simply"](https://www.writethedocs.org/videos/prague/2018/don-t-say-simply-jim-fisher/),
  a talk by Jim Fisher ([video from Write The Docs](https://youtu.be/gsT2BBWBVmM))
- ["Leveraging Accessibility and Usability to Serve Truly Diverse Audiences"](https://a11ytalks.com/posts/2020-OCT),
  a talk by Tearyne Almendariz and Kat Shaw ([slide deck](https://docs.google.com/presentation/d/112kJTTyvv4P-AVFW8-3djoA6dwc_LfCv6iaZ9xeWTD0/))
- ["Move beyond empathy: a11y in documentation](https://www.writethedocs.org/videos/portland/2020/moving-beyond-empathy-a11y-in-documentation-alexandra-white/), a talk by me, with video.

### Develop and design

- [Learn Accessibility from web.dev](https://web.dev/learn/accessibility/structure/)
- [ARIA guidelines](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA)
- [The Accessibility Cheatsheet](https://bitsofco.de/the-accessibility-cheatsheet/) by bits ofcode
- [GSA Government IT Accessibility program](https://www.section508.gov/about-us) (i.e. Section 508)
- Microsoft [inclusive design toolkit](https://www.microsoft.com/design/inclusive/)
- Smashing Magazine's [guide to designing accessibly](https://www.smashingmagazine.com/2018/04/designing-accessibility-inclusion/)

### Test

Always test your work. You can't help your users if you have no understandng of accessibility tools.

- [Tools and Techniques from W3C](https://www.w3.org/WAI/people-use-web/tools-techniques/)
- Learn Accessibility: [Automated testing](https://web.dev/learn/accessibility/test-automated),
  [manual testing](https://web.dev/learn/accessibility/test-manual),
  and [AT testing](https://web.dev/learn/accessibility/test-assistive-technology).

One caveat: If you're not a regular user of assistive technology, your experience will be different
from those who use it. Whenever possible, speak with AT users to better understand their experience
and solve for their problems.

## Events

There are a number of accessibility focused conferences:

- [Axe-con](https://www.deque.com/axe-con/)
- [ASSETS](https://assets19.sigaccess.org/)
- [#a11yTO Conf](https://conf.a11yto.com/)
- [A11yTalks](https://a11ytalks.com/)
- [Guelph Accessibility Conference](https://opened.uoguelph.ca/accessibility-conference)
