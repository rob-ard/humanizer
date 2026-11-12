---
name: humanizer
description: "Revise the full text in user-provided files so it reads naturally and specifically, preserving the writer’s voice, meaning, facts, sources, and formatting. Use when asked to humanize text or remove generic AI-like phrasing."
---

# Humanizer

Use this skill when the user asks to humanize text, make it sound more natural, or revise all the text in files they provide. Work on the full requested scope, in the original language, and preserve the document’s purpose and voice.

## Editing principles

- Preserve meaning, facts, names, numbers, quotations, citations, necessary caveats, and the author’s level of formality. Do not invent personal experiences, opinions, evidence, sources, or details to make prose seem more human.
- Prefer direct, concrete wording. Replace vague or inflated statements with specific information already present in the material. Keep technical terms when they are accurate and useful.
- Vary sentence length and structure where it improves the rhythm. Avoid making every sentence equally polished, equally short, or built from the same template. Do not add errors, slang, or artificial quirks to imitate a person.
- Review all text in scope, including headings, lists, captions, footnotes, comments, and boilerplate. Preserve layout and formatting where the file type permits. If editing a supplied file is implied, revise the file rather than returning only a sample; provide the revised text in chat when direct file editing is unavailable.
- Keep sources and citations intact. Do not silently “fix” factual claims or references by guessing. Flag material ambiguity; verify facts only when asked or when the task requires it and suitable research tools are available.

## Humanization checklist

Use the signals in [Wikipedia’s community-maintained guide](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) as an editorial lens, not a rigid blacklist. Several signs are specific to Wikipedia, and none proves authorship by itself. Focus on patterns that recur or cluster:

- Remove unsupported importance, legacy, impact, symbolism, or “broader trend” claims. Avoid promotional praise and travel-guide language when the source material does not support it.
- Cut commentary that merely announces what a fact “highlights,” “underscores,” “reflects,” or “contributes to.” Explain the evidence or implication directly when it matters.
- Replace vague relationships with the specific relationship when known. Avoid vague attributions such as unnamed experts or critics, and do not present a small number of sources as broad consensus.
- Summarize what a source says instead of emphasizing that coverage exists or describing the source landscape. Do not overstate what official records, databases, or primary sources establish.
- Watch for formulaic “challenges and future prospects” endings, generic upbeat conclusions, redundant summaries, and unnecessary “awards and recognition” sections.
- Watch for repeated AI-associated vocabulary, especially when words like “crucial,” “pivotal,” “robust,” “delve,” “tapestry,” “testament,” “underscore,” “vibrant,” “landscape,” “foster,” “enhance,” “showcase,” or their Italian equivalents appear in clusters without adding precision. These are context clues, not banned words.
- Prefer simple verbs and constructions when they say the same thing. Do not replace every “is,” “are,” or “has” with inflated phrases such as “serves as,” “represents,” or “boasts.”
- Reduce repeated contrast templates such as “not only X but also Y,” “not X but Y,” and “Y rather than X,” as well as decorative groups of three. Keep them when they are the clearest, accurate expression.
- Remove generic scene-setting, chatbot preambles or refusals accidentally pasted into a document, user-facing instructions, irrelevant knowledge-cutoff disclaimers, and unfilled placeholders. Avoid boilerplate about missing sources or limited search results; state genuine uncertainty accurately and do not speculate to fill gaps.
- Avoid mechanical synonym swapping, repetitive transitions, uniform paragraph shapes, and forced conclusions. Use natural punctuation for the language and document. Do not automatically delete em dashes, curly quotes, or other punctuation based on a single supposed AI tell.

## Wikipedia-specific checks

Apply these only when the material is intended for Wikipedia or contains Wikipedia markup. Check for title-case headings, excessive bold, inline-header lists, incorrect heading levels, emoji, inconsistent quotation marks for the target style, Markdown left in wikitext, malformed markup, chatbot citation artifacts, nonexistent templates/categories, and draft instructions or maintenance tags pasted into article text. In leads, check that a list title is not awkwardly treated as the name of a real-world entity. Watch for canned user-page sections and generic headings such as “About Me” or “Let’s Connect.”

For references, check for placeholders, broken or irrelevant links, invalid DOI/ISBN values, DOI links that identify a different work, book citations that cannot verify the claim, incorrect reference reuse, unused named references, search URLs, tracking parameters, and implausible access dates. Do not invent replacement citations; flag anything that cannot be verified.

In Wikipedia comments and edit summaries, remove copied chatbot replies, generic customer-service language, canned claims of policy compliance, excessive procedural narration, irrelevant requests for further feedback, and unnecessary inventories of citation or markup changes. In comments, watch for template-like headings, defensive claims about how much human work was done, requests for critics to specify every fix, or dismissals of authorship concerns without addressing substance. Treat sudden style changes and bulk editing patterns as context, not proof. Check claims and sourcing for bias or unsupported generalization rather than trying to hide them with stylistic edits.

## Limits and delivery

The guide is descriptive and context-dependent. Correct grammar, formal prose, one transition word, curly punctuation, or an em dash alone does not show that text was generated by AI. Do not force casualness, first person, contractions, typos, or fabricated specificity. Do not promise that a detector will accept a text or claim it is undetectable; detector scores are not a substitute for editing and are not needed unless the user asks.

After revising, briefly say which files or sections were handled and mention any unresolved factual or source issue. Show the revised text when the user asked for text in chat; otherwise keep the completion note concise.
