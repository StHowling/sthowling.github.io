# Chinese name webfont

`source-han-sans-name.woff2` is a self-hosted subset of Adobe's
[Source Han Sans 2.005](https://github.com/adobe-fonts/source-han-sans/tree/2.005R),
from `SubsetOTF/CN/SourceHanSansCN-Regular.otf`.

It contains only 史天尧 (U+53F2, U+5929, U+5C27), with the original Regular
outlines. FontTools was used to subset and compress it as WOFF2. The modified
font's internal family is renamed to `Tianyao Han Sans` to respect the reserved
font name in the SIL Open Font License. Copyright and license metadata are
retained; the full license is in `SourceHanSans-LICENSE.txt`.

The homepage uses this font at 88% of the English name's size for visual balance.
If the Chinese name changes, regenerate the subset and update the `unicode-range`
in `assets/css/editorial.css`.
