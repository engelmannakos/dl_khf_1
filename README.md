# Deep Learning: Task 1
This is a repo for the first Deep Learing task.

In the first task I had to upload 5 images that I downloaded from the internet. I reshaped the image to make it easier to get the r-g-b data from it and put thoso datas into different arrays (red, green, blue). An 'rgb' array got these arrays, and every image's 'rgb' got into a common 'rgbs' array. After that I showed the 256x256 images and after every picture I showed the histograms. These diagrams had 3 values (red, green, blue), its own colors. I counted for every image the means and the standard deviations and than I formed the arrays so if I counted these values again, I got ~0 for means and ~1 for stds.

In the second task I read two sounds and than I formed it to Integer arrays. I counted the means and standard deviations and formed the arrays the same way as before so when I counted these values again I got ~0 for means and ~1 for stds.

In the third task I had to install a library which helped me to convert the html file to string (I found it on the internet). I read the html than formed it into a page than with BeautifulSoup the html codes were gone. After that I checked every character in the text and which weren't a letter (isalpha is True if the character is a letter) I didn't care and which were a letter, I put it into an array. Than I showed the frequency of every character on a histogram (separated the lower and uppercase letter).


Ez az eső feladat repoja.

Az első feladatban 5 képet kellett betölteni, ezeket az internetről tölöttem le. A képeket újraformáltam, hogy könnyen legyen belőlük kiszedni az r-g-b értékeket a különböző (red, green, blue) listákba. Ezeket egy közös rgb listába, majd pedig egy közös rgbs nevű listába raktam. Ezek után megjelenítettem a 256x256-os képeket, majd minden kép után kirajzoltam a hisztogramjukat. Egy diagramra 3 értek (red, green, blue) került fel, minden képhez a sajátja. Kiszámoltam az összes képre a várható értéket és a szórást, majd átalakítottam úgy a listát, hogy ezeket újra kiszámolva már ~0 várható értéket kpajunk és ~1 szórást.

A második feladatban beolvastam a két hangfájlt majd átalakítottam azokat integer listákká. Ezekre ugyanúgy kiszámoltam a várható értéket és a szórást, majd ezt is átalakítottam, így itt is 0 várható értéket kaptunk és 1 szórást. Ezután megjelenítettem mindkét diagramot.

A harmadik feladatban először telepítenem kellett a beautifulshop4 könyvtárat, amely segített a html szöveggé alakításában (az interneten találtam). A htmlt beolvastam, majd oldallá alakítottam és végül a BeautifulSouppal a html kódrészletek eltűntek. Ezután végigmentem a szöveg összes karakterén, és ami nem betű volt (az isalpha akkor True, ha karakter betű) azt átugrottam, ami pedig betű volt, azt beraktam egy listába. Majd egy hisztogramban megjelenítettem a betűk gyakoriságát, különvéve a kis- és nagybetűket.
