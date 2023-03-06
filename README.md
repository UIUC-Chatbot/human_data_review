# Expert Review of Electrical Engineering Questings

# Usage instructions. Read completely before starting (it's short)!

It's very simple. Goal: Evaluate whether the _question_ and _answer_ answer are reasonable. 

1. To start: `cd human_data_review/gpt-3_semantic_search && python Human_Filtering.py`

It will resume from wherever the last person left off. So **please commit & push as soon as you finish your work**. If you face merge conflicts, open up VS-Code and make sure to "accept both" changes. 

`Just enter a single number from 1 (best) to 3 (garbage) and press enter.`

```text
1. ⭐️ Top Quality: Impressive, clear, coherent, complete ideas. 
    Please have a high bar for quality, about 20% of items should hit this quality. 
2. 👍 Decent: Maybe not super impressive detail, but still generally clear and correct. 
    Slightly incomplete sentences are ok, but if it's too random for you to understand, 
    just delete it. About 50% of items shuold fit this quality.
3. 🚫 To delete: Incomplete ideas, unrelated questions and answers, random or 
    'hallucinated' rambling. Roughly 30% should fit this quality. 
```

3. To exit press `ctrl+c` (same on windows/mac/linux). Then **you must press `y` to save your changes**. Or you can press `n` to discard changes (there is no undo for this step!). 

4. Immediately `git commit -a` & `git push` your changes so others can build on your work. 

Thank you for your help!!
For any help, email me kvday2@illinois.edu.
