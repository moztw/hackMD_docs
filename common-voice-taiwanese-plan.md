# 台語 Common Voice 計畫共筆
Shared-notes of Taiwanese in Common Voice planning


## Language Code: nan-tw

Specific for "Minnan in Taiwan" (Taiwanese)

- ISO 639-3 defined [nan](https://iso639-3.sil.org/code/nan) as Minnan (Hokkien), the code is shared by Taiwanese Hokkien, Hokkien in Southeastern China and Hokkien in Southeastern Asia.
- Due to words differences, political sensitive sentences (for China) and different Latin/phenotic system of Taiwan to China, we suggested add tw to nan to specify the locale is for Taiwanese. 

## 網站介面 UI translation on Pontoon

### options
1. *(prefer)* Translate UI into Taiwanese
    - language code: nan-tw
    - Han character (漢字) with Tâi-lô (TL, 台羅) phenotic system
        - Fork zh-tw into nan-tw at the beginning, Taiwanese community will translate Taiwan Mandarin into Taiwanese one by one
            - The translation progress don't need to be a blocker.
2. Use zh-tw UI directly without new ponton locale
    - It won't be problem for website user, because more than 99% of the potential recorder should be able to read Chinese
        - (Irvin) I believe there won't be any user that can only read Taiwanese 
    - People from Taiwanese language community present strongly disagree with this option due to it's implicit that Taiwanese is like sub-language of Taiwan Mandarin.

## 句庫 Text Corpus

### Writing system options
1. All Han characters
    - Follow the MOE (Ministry of Education) standard
2. All Latin alphabet (Lô-má-jī)
    - Problems: When multiple accents available, which should be spelled?
    - Should we list all the accents as different sentences and ask people to record according to the spelling? 
        - No, we shouldn't ask people to pronounciate in non-native accents.
3. *(prefer)* Mainly Han chars, supplemented by Lô-má-jī
    - Lô-má-jī is only used when the word
        - is rare or the pronunciation is ambiguous
        - has a variety of readings and must be marked
        - has no corresponding Han characters
        - cannot be displayed on mobile or older devices (...tbd)
    - examples:
        - 上（siōng/siāng）愛食番仔番薯（han-tsî/han-tsû/han-tsîr/an-tsîr）
        - 嫁著做田翁，無法梳頭鬃。
        - 人肉鹹鹹，袂食得。
        - 媽祖宮起毋著面，痟的（siáu--ê）出袂盡。
        - 一千銀（gîn/gûn/gîrn），毋值四兩命（miā）。
        - 七七四十九（sù/sìr-si̍p-kiú），問娘何月有（iú），除卻（tû/tîr/tî-khioh）母生年，再添一十九（it-si̍p-kiú）。
        - 七月頓頓飽，八月攏無巧（khá）。
        - 三个錢尪仔，栽四个錢喙鬚（tshuì-tshiu）。
        - 了錢生理無人做，刣頭生理有人做。
        - 五支指頭仔咬起來逐支嘛疼（thiànn）。
        - 二更更（kinn/kenn），三暝暝，四算錢，五燒香，六拜年。
        - 交陪醫生腹肚做藥櫥，交陪牛販仔（gû-huàn-á）駛瘦牛。
        - 人無橫財（huâinn/huînn/hirînn-tsâi）袂富，馬無野草袂肥。
        - 偷食袂瞞得喙齒，討翁袂瞞得鄉里。
        - 棚頂（pênn/pînn-tíng）做甲流汗，棚跤（pênn/pînn-kha）嫌甲流瀾。 
        - 兄弟若手足（tshiú-tsiok/siú-tsiok），某囝（bóo-kiánn/kánn/ngá）若衫褲。
        - 勸人𬦰（peh）上樹，樓梯攑（gia̍h）咧走。
        - 南斗註生，北斗註死。
        - 呂洞賓葫蘆內的藥，醫別人無醫家己（ka-kī/ka-tī/kai-kī/kāi-kī）。
        - 和（hām）好人行，有布通經；和歹人行，有囝通生。
        - 善的掠來縛，惡的放伊去。

