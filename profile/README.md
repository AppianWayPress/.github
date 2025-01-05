# Appian Way Press

The Appian Way Press is a small publisher based in Washington state and has traditionally published works created and edited by its sole proprietor, [Rick Brannan](https://github.com/RickBrannan).

However, there are a tremendous amount of works of early Christianity, valuable both to scholars and the church, that have either never been translated or only have old and difficult to understand translations that were published decades ago.

The Appian Way Press has decided to use tools from the ever-growing field of machine learning (ML) and specifically machine translation (MT), combined with the growing capability of large-language models (LLMs) to attack this problem.

## What Resources are Available?

The Appian Way Press is using LLMs (specifically `gpt-4o-mini`) to do intitial translations from classical Greek to English. We're starting with editions available from the Open Greek and Latin's [First1KGreek project](https://github.com/opengreekandlatin/First1KGreek), which aims to provide high-quality data for the Greek works of the first millenium. We will initially select resources from this repository to translate and create open, readable English translations and make them available for download.

We plan on creating diglot editions of each work, with the original on the left and the translation on the right. Because the translation is machine-created, it is important to remain transparent with the original source. We will also make epub editions available for download. We are evaluating audiobook editions of the translations as well.

Because Open Greek and Latin licenses all of their material with a CC-BY-SA 4.0 license, our translations, which are derivative of them, will be under the same license. This means that scholars can take the translations as starting points to review, edit, and create their own editions, and make them available to others as well.

We will also release reasonably-priced paperback editions of the translations (not diglots) through Amazon so that those who desire hard copies to read and evaluate will be able to do so.

## What are the books?

We're starting small because this is a bit of a complicated project. But we anticipate our initial release to include the following in diglot and epub form as well as paperbacks from Amazon:

* [Epiphanius](https://github.com/AppianWayPress/Epiphanius)
  * _The Well-Anchored One_
* [Eusebius](https://github.com/AppianWayPress/Eusebius)
  * _The Preparation of the Gospel_
  * _The Proof of the Gospel_
  * _History of the Church_
  * _On Ecclesiastical Theology_
* [Origen](https://github.com/AppianWayPress/Origen)
  * _Against Celsus_

The diglot and paperback editions of these volumes (so, not the epub editions) will have indexes as well:

* Index of Person Names
* Index of National and Religious Groups
* Index of Places
* Index of Bible References

We anticipate more volumes. The following volumes are on our "short list" to evaluate:

* Athenagoras’ _On the Resurrection of the Dead_
* Epiphanius’ _Panarion_
* Theophilus of Antioch’s _Ad Autolycum_

## Can works be suggested?

Sure. You can email `info@appianwaypress.com`. If, however, your suggestion is not available in the First1KGreek repo, it is very unlikely it will be pursued.

## Trusting AI is stupid. Why are you even doing this?

We agree that trusting AI is stupid. That's why we've done a number of experiments to review the output of `gpt-4o-mini` translating non-Biblical Greek into English. It's actually pretty decent, but not perfect. So we do other evaluations of the text, notably a semantic comparison of the original text to the translation, at the verse/paragraph level, to ensure that the translation communicates the meaning of the original. We also employ a method of checking translation length at the paragraph/verse level against what an expected translation length would be in an effort to identify possible areas of hallucination (either addition or omission).

## There are so many ethical issues involved with AI and LLM models. Why are you even doing this?

We agree there are some issues particularly concerning how some of the LLM models were produced and how they are sustained. Where possible, we prefer to use non-LLM ML techniques (such as we use for semantic comparison and for creating indexes). We looked at available MT solutions for translating English from ancient Greek, and they were all subpar for our use case. This is one reason why we are focusing on works that have not been translated in recent decades or works that have never been translated. If there is a solid and relatively recent translation, that translation should be supported where it is also not overly expensive to obtain. If no recent and accessible translation exists, then making one available and accessible is, we think, an acceptable use of the technology. Particularly if the information we create can be used to create a full, edited translation with notes and/or commentary by someone else. We hope to be the platform to enable further work on these valuable editions to make them more accessible and more easily understood.
