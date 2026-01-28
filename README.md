# Malavedan Script Font

This is the first font ever made of the recently-constructed script for the endangered Malavedan language _ChathiPaani_, a Dravidian language of Kerala and Tamil Nadu that is closely related to Malayalam.  

This font project was requested by a person of the Malavedan tribe who reached out to me on Reddit.  

_Image shows font at version 0.950. Download from [Releases page](https://github.com/fazzaan/font-malavedan-abugida/releases)._ 
<img width="1011" height="1080" alt="image" src="https://github.com/user-attachments/assets/51db3b9e-0764-4496-a2c9-78a1d21d9235" />

I'd say you can read more at the following links, but there's really not much information online.  
Notably, none of these pages seem to mention the _Chathi_ subgroup or language.  

<details>
  <summary>Click to see links</summary>
  
* [https://en.wikipedia.org/wiki/Malavedan_language](https://en.wikipedia.org/wiki/Malavedan_language)  
* [https://www.ethnologue.com/language/mjr/](https://www.ethnologue.com/language/mjr/)
* [https://www.wikidata.org/wiki/Q12952775](https://www.wikidata.org/wiki/Q12952775)  
* [https://glottolog.org/resource/languoid/id/mala1463](https://glottolog.org/resource/languoid/id/mala1463)
* [https://globalrecordings.net/en/language/13414](https://globalrecordings.net/en/language/13414)
* [https://anythingtranslate.com/translators/malavedan-malayalam-script-translator/](https://anythingtranslate.com/translators/malavedan-malayalam-script-translator/) (I have no idea how this works or if it's remotely correct)
* [https://dbpedia.org/page/Malavedan_language](https://dbpedia.org/page/Malavedan_language)
* [https://www.thehindu.com/news/national/kerala/dlsa-adopts-tribal-settlement/article69382094.ece](https://www.thehindu.com/news/national/kerala/dlsa-adopts-tribal-settlement/article69382094.ece) 

</details>

## About Malavedan script

The script's symbols in the font are (will be) bound to their own unicode range (the [PUA](https://en.wikipedia.org/wiki/Private_Use_Areas)) and directly to the Latin (English) QWERTY layout.  

This Malavedan (_Malai Vedan_, IPA: [mɐlɐʋeːɖɐn]) script is an abugida, with visual and structural similarities to the Malayalam script.  

This Malavedan script uses 17 diacritics in total:  
* to mark 11 vowels (in addition to the inherent a)  
* a circle, for a nasal coda, perhaps similar to the anusvara of Devanagari
* a dot above, I think to mark if a letter takes syllable-final sound  
* a u above, for the removal of the inherent a, perhaps similar to the halant of Devanagari  
* a ring above, to join two consonants directly together (stronger than the 'anusvara')
* a breve below, to add an /ɹ/-like sound to the consonant
* a dot below, to indicate the corresponding letters of Malayalam that aren't present in Malavedan pronunciation  

From the tribe member who requested this font:  
> "This is for the Malavedan tribe. The name of our language is _ChathiPaani_. Chathi denotes our tribe and Paani means _language_ or _word_. Very few people are using this language in this time, the rest of them are using Malayalam."  


___

# To Do
- [x] ~~add numbers~~
- [x] ~~add basic punctuation and symbols~~
- [ ] attach glyphs to sensible unicode range in PUA  
- [ ] build basic website to host fonts, text and dictionary of Malavedan language (put in separate github repository)  
- [ ] create conversion script to convert between QWERTY encoding and PUA encoding (and future dedicated unicode range when it's been accepted by the Unicode Consortium)
- [ ] draft submission proposal for the Unicode Consortium for Malavedan
