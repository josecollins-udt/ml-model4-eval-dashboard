# Model 4 preliminary eval (GitHub Pages)

Static copy of the localhost Streamlit dashboard. Interactive Plotly hover. No Streamlit server. **No `user_id`.**

Live: https://josecollins-udt.github.io/ml-model4-eval-dashboard/

CB user = lifetime `user_id IN fraud.cb_payments`. Scores `> 1` are ignored in the plots.

Rebuild after the Streamlit cache changes:

```
python generate_share_pages.py
```

from `Python/ml_model4_eval/`. Then commit the files in this folder.
