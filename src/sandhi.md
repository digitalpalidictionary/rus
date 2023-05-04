# Compound Deconstruction and Sandhi Splitting

## Some Background

Sandhi compounds are the greatest hurdle to any beginner learning Pāḷi. The rules of sandhi are not absolute rules, only morphing possibilities according to context. These rules are complex and difficult for a beginner to understand.

The situation only gets worse in the commentaries where it is not uncommon to have extremely long compounds, including such monsters as *avippavāsasammutisanthatasammutibhattuddesakasenāsanaggāhāpakabhaṇḍāgārikacīvarappaṭiggāhakayāgubhājakaphalabhājakakhajjabhājakaappamattakavissajjakasāṭiyaggāhapakapattaggāhāpakaārāmikapesakasāmaṇerapesakasammutīti*,  *bhattuddesakasenāsanaggāhāpakabhaṇḍāgārikacīvarapaṭiggāhakacīvarabhājanakayāgubhājanakaphalabhājanakakhajjabhājanakaappamattakavissajjakasāṭiyaggāhāpakapattaggāhāpakaārāmikapesakasāmaṇerapesakasammutīnaṃ* and *āsavavippayuttasāsavasaṃyojanavippayuttasaṃyojaniyaganthavippayuttaganthaniyanīvaraṇavippayuttanīvaraṇiyaparāmāsavippayuttaparāmaṭṭhakilesavippayuttasaṅkilesikapariyāpannasauttaradukāta*.

Sandhi is the greatest hurdle facing all forms of computational linguistics related to the Pāḷi canon. At the moment it is blocking any real development in the field. 

No-one has cracked this puzzle in any way that comes close to a satisfactory solution.

The only present solution that is in any way useful is the [DPR analysis function](https://www.digitalpalireader.online/_dprhtml/index.html?loc=m.0.0.0.0.1.2.m&analysis=cakkhundriyasa.mvarasa.mvuto&frombox=1), which is wrong and misleading as often as it is right. Apparently the method it uses is a system of regex substitutions to remove inflections and reduce compounds to dictionary words.

## A New Approach

One of the useful outputs of the Digital Pāḷi Dictionary is a list of inflections for every word in the dictionary. This, together with a set of [letter transformation rules](https://github.com/digitalpalidictionary/inflection-generator/blob/main/sandhi/sandhi%20rules.csv) has been employed to create a new sandhi-splitting algorithm. 

It is still a work in progress and far from perfect - an intelligence will always be required to discern context - but it is better than anything else which currently exists, giving more accurate results and, most importantly, fewer false positives. 

For instance, If you open *bahalamadhukatelanāgabalapicchillādīnaṃ* in DPD, it will show the breakup, which can be clicked on to take you to the relevant words.

![sandhisplitter](pics/sandhi/bahalamadhukatelanāgabalapicchillādīnaṃ.png)

Currently this feature is available for the following books in the Pāḷi corpus.

- **Vinaya** mūla and aṭṭhakathā
- **Sutta** mūla and aṭṭhakathā
- **Abhidhamma** mūla and aṭṭhakathā
- **Visuddhimagga** and Visuddhimagga Mahāṭīkā

Actually the sandhi splitting is completed for the entire Chaṭṭha Saṅgāyana corpus, but the data set or 700 000 words is too large to incorporate into the GoldenDict or MDict format. If you would like a custom dicitonary of sandhi-splitting data for some obscure corner of the Pāḷī corpus, please get in touch and I will be happy to provice you with that. 
