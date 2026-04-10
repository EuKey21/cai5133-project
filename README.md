# Project Notes

## Data Setup
Download the Yelp dataset from the Yelp Open Dataset page, then unzip all files into:

- `./yelp_dataset/`

Expected files include:
- `yelp_academic_dataset_business.json`
- `yelp_academic_dataset_checkin.json`
- `yelp_academic_dataset_review.json`
- `yelp_academic_dataset_tip.json`
- `yelp_academic_dataset_user.json`

## Notebooks (Root)
- `json_preview.ipynb`: Quick inspection notebook for previewing Yelp JSON/JSONL data and checking schema/columns.
- `preprocessing.ipynb`: Feature-engineering pipeline notebook for filtering reviews, building primary/secondary features, combining outputs, and saving test artifacts. The resulted data is about 1 GB.
