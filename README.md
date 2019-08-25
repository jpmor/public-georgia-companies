
## Usage

https://finviz.com is great for comparing companies, and free.

Run the following script:

```
export FVURL="https://finviz.com/bubbles.ashx\?x=employees&y=perfYtd&size=marketCap&color=sector&idx=any&tickers=";
open "${FVURL}$(awk 1 ORS=' ' symbols.txt)"
```
