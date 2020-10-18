# scout

Work on the CMS 40MHz scout project under Konstantinos Theofilatos's supervision.

## Runing the code guide:
1. You must have the data/hiion folder (provided by Mr. Theofilatos) in the same location as these programs.
2. Run DataFileCleaning.ipynb to remove empties and merge runs split into multiple runs. (Note: It does nothing to .monitor.txt files)
3. Run Run Certification.ipynb to save the good and bad runs into their respective folder.
4. Run MergeData.ipynb to merge all the "good" runs together as if they are one run or get all the 2Legged muons from merged with a specified ΔBx. 
4. Rates.ipynb is a typical analysis on merged.txt, while ReferenceRunQuickAnalysis.ipynb is a quick analysis on scout_326822_000000.txt .
5. RatePerTime.ipynb studies the relationship of the characteristics (duration, rectime, rate) of different runs. (Needs Fix)
