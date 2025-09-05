# **Guidelines – Transcriboquest 2025**

Participants : Augé Sophie, Dedieu Alexia, Jambe Ariane, La Veglia Andrea, Rousseau Nathalie, Vergara Claudio  
Trainers : Federica Nicolardi, Marianne Reboul

Introduction : This document outlines a proposed set of transcription guidelines for the Handwritten Text Recognition (HTR) of Ancient Greek documents, intended to support the development of generalizable and robust HTR models. This document is based on the existing work in progress from TranscriboQuest2024 and DH2025 (Maxime Guénette,  Marianne Reboul, Mathilde Verstraete, Mathenia Vlachou Efstathiou). For further reference : Ὅσοι ἄνθρωποι, τοσαῦται γνῶμαι. Harmonizing Guidelines for Handwritten Text Recognition of Ancient Greek, DH2025, Lisbon, July 14-18th, 2025\. [https://dhtr25.anthologiagraeca.org/](https://dhtr25.anthologiagraeca.org/)).

1. # Abbreviations

| Image | Explanation | Unicode representation | Code |
| :---- | ----- | :---- | :---- |
| ![](./images/image1.png) | \-εν | ⸦ | U+2E26 |
| ![](./images/image2.png) | \-ον | \\ | U+1D23B |
| ![](./images/image3.png) | \-ων  | ͡  | U+0361 |
| ![](./images/image4.png) | \-οις | ᓓ | U+14D3 |
| ![](./images/image5.png) | καὶ | ϗ | U+03D7 |
| ![](./images/image6.png) | ? | ⌇ | U+2307 |
| ![](./images/image7.png) | \-ιν | ◠ | U+25E0 |
| ![](./images/image8.png) | \-ους | ჯ | U+10EF |
| ![](./images/image9.png) | \-ως | ᕋ | U+154B |
| ![](./images/image10.png) | \-ασ | ✓ | U+2713 |
| ![](./images/image11.png) | γγ | സ | U+0D38 |
| ![](./images/image12.png) | σε (?) | ̷  | U+0337 |
| ![](./images/image13.png) | ην | ^ | U+005E |
| ![](./images/image14.png) | \-ειν | ˶ | U+02F6 |
| ![](./images/image15.png) | \-μ+αι Lower final sign for contracting  \-αι mid and end of word | μƫ | letter \+ U+01AB |
| ![](./images/image16.png) | Upper final sign for ως | ᖦ  | U+15A6 |
| ![](./images/image17.png) | upper final vertical sign | ᕊ  | U+154A |
| ![](./images/image18.png) | θαι | ſ | U+017F |
| ![](./images/image19.png) | αι | 𐤍 | U+1090D |
| ![](./images/image20.png) | φησι(ν) | ⍎ʰ | U+234E+U+02B0 |
| ![](./images/image21.png) | φασι(ν) | ⍎ᵃ | U+234E+ᵃ |
| ![](./images/image22.png) | περὶ | πᵉ | U+03C0 \+ U+1D49 |

2. # Ligatures

   **⚠ Warning :** it has been discussed that ***ligatures*** should be developed if their representation could visually contain part of the letters included. When ligatures are completely graphically different from their meaning, it could be replaced by a potential corresponding unicode character.

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image23.png) | \-ει | ? | ? |
| ![](./images/image24.png) | ἑβ | ἑβ |  |
| ![](./images/image25.png) | εξ | εξ |  |
| ![](./images/image26.png) | έσθ | έσθ |  |
| ![](./images/image27.png) | κατὰ | κᵗ |  |
| ![](./images/image28.png) | ἐτ | ἐτ |  |
| ![](./images/image29.png) | ευ | ευ  | U+1D49 \+ U+03C5 |
| ![](./images/image30.png) | επ | ᵉπ | U+1D49 \+ U+03C0 |
| ![](./images/image31.png) | ετ | τᵉ | U+03C4 \+ U+1D49 |
| ![](./images/image32.png) | εἰ | εἰ |  |
| ![](./images/image33.png) | εγ | εγ |  |
| ![](./images/image34.png) | στ | ᓕ  | U+14D5 |
| ![](./images/image35.png) | ου | ж  | U+0436  |
| ![](./images/image36.png) | ει | Ⴁ  | U+10A1 |
| ![](./images/image37.png) | καὶ σωτHρας | ϗ σωτHρας | U+03D7 |
| ![](./images/image38.png) | \-ρο- | ల | U+0C32 |
| ![](./images/image39.png) | τῶν | ȸ \+ ῀ | U+0238 \+ U+1FC0 |

3. # SuperScripts

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image40.png) | Transcribe at the end of the final “π” as superscript | φίλιππᵉ | U+1D49 |

4. # LowerScripts

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image41.png) | Α expunctuated (= cancelled) | Α̣ | U+0323 \+ the dotted letter |
| ![](./images/image42.png) | Σ expunctuated with a dot both below and above  | Σ̣̇ | Σ  \+ U+0307 (dot above) \+  U+0323 (dot below) |

5. # Nomina Sacra

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image43.png) | ἀνθρώπων | ἀνών¯ | U+00AF |
| ![](./images/image44.png) | πατρὸς | πρς¯\` | U+00AF \+ U+0060 |

6. #  Letters : allographs

   **⚠ Warning :** it has been discussed that ***allographs*** should be maintained in their primary form.  
   Example :

σ:  ![](./images/image45.png) ![](./images/image46.png)/![](./images/image47.png)  ![](./images/image48.png)  
π: ![](./images/image49.png) ![](./images/image50.png)  
β: ![](./images/image51.png) ![](./images/image52.png)

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image53.png) | omega capital  | Ω | U+03A9  |
| ![](./images/image54.png) | lunate sigma capital | Σ | U+03A3 |
| ![](./images/image55.png) | lambda above another letter | ^  | U+005E |
| ![](./images/image56.png) | ε | ε | U+03B5 |
| ![](./images/image57.png) | ε | Ε | U+0395  |
| ![](./images/image58.png) | capital alpha above sampi \= Α’ \= 1.000 | A' | U+0027 |

7. # Deletions

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image59.png) | Erased letter Cf. https://catmus-guidelines.github.io/html/guidelines/en/corrections\_and\_others.html | ⟦θ⟧  | U+27E6 (opening) U+27E7 (closing) |

8. #  Insertions

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
|  | ἀπαταιῶνος with αι striked through, corrected with an ε interlinear (=ἀπατεῶνος) | ἀπατ~~α~~ᵉιῶνος | U+002F \+ U+1D49 (/ and ᵉ) |
| ![](./images/image60.png) | insertion of a δ in the supralinear space  | ΒΟΡΕΑᴰΙΑι | U+1D30 |

9. # Punctuation marks

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image61.png) | paragraphos | ⸏ | U+2E0F  |
| ![](./images/image62.png) | end of an epigram | :— | U+003A \+ U+2014 |
| ![](./images/image63.png) | start of an epigram | ⨍ | U+2A0D |
| ![](./images/image64.png) | start of an epigram | \- | U+002D |
| ![](./images/image65.png) | coronis | ⸎ | U+2E0E |

10. # Numerals

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image66.png) | 10 (indicate numerals with a macron (¯) above or after the number) | ι̅ | U+00AF |
| ![](./images/image67.png) | 10 (indicate numerals with a macron (¯) above or after the number) | ιβ̅ | U+00AF |

11. # Miscellaneous

| Image | Explanation | Unicode representation | Code |
| :---: | :---: | :---: | :---: |
| ![](./images/image68.png) | pointed asterisk | ※  | U+203B |
| ![](./images/image69.png) | ? | ⁘  | U+2058 |
| ![](./images/image70.png) | ? | : ⎯  | U+003A \+ U+23AF |
| ![](./images/image71.png) | ? | ⩫  | U+2A6B |
| ![](./images/image72.png) | ? | ¬  | U+00AC |

# 















































































































































