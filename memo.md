<pre>
用 python 呼叫 pdf2text , 把某年醫師國考題目答案, 組成 MMLU 的格式 

用 lm-evaluation-harness 去評估
TMMLU+ 評  perplexity R1 1776
台灣某年醫師國考第一階段+第二階段 (大約 480 ~600  題 )評  perplexity R1 1776
台灣某年醫師國考第一階段+第二階段 (大約 480 ~ 600 題 )評  Open AI o1

然後再去分析結果 , 看看是繁體詞彙理解不夠, 還是專業知識不足

</pre>
---

其他暫存:

預訓練資料集: fineweb-zhtw , 107 GB , 預估 Token 數： 72B
https://huggingface.co/datasets/voidful/fineweb-zhtw


https://github.com/EleutherAI/lm-evaluation-harness

https://huggingface.co/datasets/cais/mmlu

https://bcoct.naer.edu.tw/TBCL/

2023 華語文語料庫與能力基準應用競賽得獎作品 https://coct.naer.edu.tw/page.jsp?ID=56

語料庫覆蓋率統計系統 https://coct.naer.edu.tw/coverage.jsp

https://github.com/konsheng/Sensitive-lexicon

TAIDE
評測資料連結 https://huggingface.co/datasets/taide/taide-bench
評測方法程式碼 https://github.com/taide-taiwan/taide-bench-eval

Project TAME 的 benchmark : TMLU ( 有 paper , 但沒找到題目沒開放出來)
https://arxiv.org/pdf/2403.20180

TMMLU+ 
https://huggingface.co/datasets/ikala/tmmluplus

聯發科的評估套件 : 
https://huggingface.co/datasets/MediaTek-Research/TCEval-v2

數發部AI產品與系統評測中心 的題目範例
https://www.aiec.org.tw/Home/DownloadZone

呼籲要開發 benchamrk 的老師們:

李宏毅老師:
https://www.facebook.com/pofeng/posts/pfbid0SS4iGTzvGH5foXmmX4bukkmoUfRn3PvD6Gj525ZHvFbyJb152vHWGkyTfuZRXM2dl

簡立峰老師:
https://www.facebook.com/pofeng/posts/pfbid02bUGkG3py1NRLBjsqECdyQgnc5nfnz6rDQQFEPepQQM1yjPtNJbLFHNrrW9HSq3C6l

鄭紹鈺老師
https://www.facebook.com/share/p/18jE2gB5QC/
