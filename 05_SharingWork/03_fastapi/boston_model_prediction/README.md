# Boston Model Prediction API

Script `boston_api.py` shows PoC example of how one can deploy the `sklearn` model.
Note that this implementation lacks a lot of key parts like:

1. Data validation
2. Data preprocessing, filling `NA` like during training.
3. Errors handling

Run with:

```
uvicorn boston_api:app
```
