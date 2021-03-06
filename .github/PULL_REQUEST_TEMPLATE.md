<!--- Briefly describe what you're changing. -->

## Description
<!--- If necessary, go into depth of what this pull request is doing. -->

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] **I am associating a language with a new file extension.**
  - [ ] The new extension is used in hundreds of repositories on GitHub.com
    - Search results for each extension:
      <!-- Replace FOOBAR with the new extension, and KEYWORDS with keywords unique to the language. Repeat for each extension added. -->
      - https://github.com/search?utf8=%E2%9C%93&type=Code&ref=searchresults&q=extension%3AFOOBAR+KEYWORDS+NOT+nothack
  - [ ] I have included a real-world usage sample for all extensions added in this PR:
    - Sample source(s):
      - [URL to each sample source, if applicable]
    - Sample license(s):
  - [ ] I have included a change to the heuristics to distinguish my language from others using the same extension.

- [ ] **I am adding a new language.**
  - [ ] The extension of the new language is used in hundreds of repositories on GitHub.com.
    - Search results for each extension:
      <!-- Replace FOOBAR with the new extension, and KEYWORDS with keywords unique to the language. Repeat for each extension added. -->
      -  https://github.com/search?utf8=%E2%9C%93&type=Code&ref=searchresults&q=extension%3AFOOBAR+KEYWORDS+NOT+nothack
  - [ ] I have included a real-world usage sample for all extensions added in this PR:
    - Sample source(s):
      - [URL to each sample source, if applicable]
    - Sample license(s):
  - [ ] I have included a syntax highlighting grammar.
  - [ ] I have included a change to the heuristics to distinguish my language from others using the same extension.

- [ ] **I am fixing a misclassified language**
  - [ ] I have included a new sample for the misclassified language:
    - Sample source(s):
      - [URL to each sample source, if applicable]
    - Sample license(s):
  - [ ] I have included a change to the heuristics to distinguish my language from others using the same extension.

- [ ] **I am changing the source of a syntax highlighting grammar**
  <!-- Update the Lightshow URLs below to show the new and old grammars in action. -->
  - Old: https://github-lightshow.herokuapp.com/
  - New: https://github-lightshow.herokuapp.com/

- [ ] **I am adding new or changing current functionality**
  <!-- This includes modifying the vendor, documentation, and generated lists. -->
  - [ ] I have added or updated the tests for the new or changed functionality.
