# Appian Way Press

The Appian Way Press is a small publisher based in Washington state and has traditionally published works created and edited by its sole proprietor, [Rick Brannan](https://github.com/RickBrannan).

However, there are a tremendous amount of works of early Christianity, valuable both to scholars and the church, that have either never been translated or only have old and difficult to understand translations that were published decades ago.

The Appian Way Press has decided to use tools from the ever-growing field of machine learning (ML) and specifically machine translation (MT), combined with the growing capability of large-language models (LLMs) to attack this problem.

Are you interested in supporting this work? You can do it through [Github Sponsors](https://github.com/sponsors/RickBrannan) or something as simple as [Buy me a Coffee](https://buymeacoffee.com/rickbrannan).

## What Resources are Available?

The Appian Way Press is using LLMs (specifically `gpt-4o-mini`) to do intitial translations from classical Greek to English. We're starting with editions available from the Open Greek and Latin's [First1KGreek project](https://github.com/opengreekandlatin/First1KGreek), which aims to provide high-quality data for the Greek works of the first millenium. We will initially select resources from this repository to translate and create open, readable English translations and make them available for download.

We plan on creating diglot editions of each work, with the original on the left and the translation on the right. Because the translation is machine-created, it is important to remain transparent with the original source. We will also make epub editions available for download. We are evaluating audiobook editions of the translations as well.

Because Open Greek and Latin licenses all of their material with a CC-BY-SA 4.0 license, our translations, which are derivative of them, will be under the same license. This means that scholars can take the translations as starting points to review, edit, and create their own editions, and make them available to others as well.

We will also release reasonably-priced paperback editions of the translations (not diglots) through Amazon so that those who desire hard copies to read and evaluate will be able to do so.

## What are the books?

We're starting small because this is a bit of a complicated project. But we anticipate our initial release to include the following in diglot and epub form. We're considering the possibility of paperbacks from Amazon:

* [Apocryphal Acts](https://github.com/AppianWayPress/ApocryphalActs)
  * _Acts of Barnabas_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/diglot/diglot-ActaBarnabae.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/epub/epub-ActaBarnabae.pdf))
  * _Acts of John_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/diglot/diglot-ActaJoannis.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/epub/epub-ActaJoannis.pdf))
  * _Acts of Philip_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/diglot/diglot-ActaPhilippi.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/epub/epub-ActaPhilippi.pdf))
  * _Acts of Thomas_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/diglot/diglot-ActaThomae.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/ApocryphalActs/main/epub/epub-ActaThomae.pdf))
* [Clement of Alexandria](https://github.com/AppianWayPress/ClementAlexandria)
  * _Can the Rich Be Saved?_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/ClementAlexandria/main/diglot/diglot-QuisDives.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/ClementAlexandria/main/epub/epub-QuisDives.pdf))
* [Clement of Rome](https://github.com/AppianWayPress/ClementRome)
  * _Pseudo-Clementine Homilies_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/ClementRome/main/diglot/diglot-Homilies.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/ClementRome/main/epub/epub-Homilies.pdf))
* [Epiphanius](https://github.com/AppianWayPress/Epiphanius)
  * _The Well-Anchored One_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/Epiphanius/main/diglot/diglot-Ancoratus.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/Epiphanius/main/epub/epub-Ancoratus.pdf))
* [Eusebius](https://github.com/AppianWayPress/Eusebius)
  * _The Preparation of the Gospel_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/diglot/diglot-Preparation.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/epub/epub-Preparation.pdf))
  * _The Proof of the Gospel_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/diglot/diglot-Demonstration.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/epub/epub-Demonstration.pdf))
  * _History of the Church_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/diglot/diglot-HistoryChurch.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/epub/epub-HistoryChurch.pdf))
  * _On Ecclesiastical Theology_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/diglot/diglot-EcclTheology.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/Eusebius/main/epub/epub-EcclTheology.pdf))
* [Origen](https://github.com/AppianWayPress/Origen)
  * _Against Celsus_ ([diglot](https://raw.githubusercontent.com/AppianWayPress/Origen/main/diglot/diglot-ContraCelsus.pdf) | [epub](https://raw.githubusercontent.com/AppianWayPress/Origen/main/epub/epub-ContraCelsus.pdf))

The diglot and (when available) paperback editions of these volumes (so, not the epub editions) will have indexes as well:

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
