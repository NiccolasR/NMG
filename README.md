---
dataset_info:
  features:
  - name: review_id
    dtype: string
  - name: user_id
    dtype: string
  - name: business_id
    dtype: string
  - name: review_stars
    dtype: float64
  - name: text
    dtype: string
  - name: date
    dtype: string
  - name: name
    dtype: string
  - name: address
    dtype: string
  - name: city
    dtype: string
  - name: state
    dtype: string
  - name: postal_code
    dtype: string
  - name: latitude
    dtype: float64
  - name: longitude
    dtype: float64
  - name: categories
    dtype: string
  - name: __index_level_0__
    dtype: int64
  splits:
  - name: yelp_restaurant_CA_2021
    num_bytes: 14130407
    num_examples: 18400
  download_size: 7537625
  dataset_size: 14130407
configs:
- config_name: default
  data_files:
  - split: yelp_restaurant_CA_2021
    path: data/yelp_restaurant_CA_2021-*
---
