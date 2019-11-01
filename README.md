# Dataset:

​	  JD IJCAI19

# Description:

This dataset is used for research on user profiling in "Semi-supervised User Profiling with Heterogeneous Graph Attention Networks", which is published in IJCAI 19. https://www.ijcai.org/proceedings/2019/0293.pdf

We randomly sampled 100,000 users from JD.com, one of the largest e-commerce sites in the world.
Then we collect the users' profiles, click and order logs ranging from Feb 2018 to Feb 2019, and the information of items (i.e. products).
This dataset contains user profiles (gender, age), user's click and order behaviors and product metadata (category information, brand, price, titles).

# Download link:

To protect the privacy of users, we only provide samples of the dataset here (i.e. top 1000 lines of each file). If you are interested in using the whole dataset for your research, please send your email to guyulongcs@gmail.com.

# Statistics:


| Type       | Count      | File       | Desc                            |
| ---------- | ---------- | ---------- | ------------------------------- |
| users      | 100,000    | user       | users                           |
| user_click | 52,983,324 | user_click | users’ click logs               |
| user_order | 1,458,499  | user_order | users’ order logs               |
| items      | 6,882,867  | item_info  | information of items (products) |

# Research Topics:

This dataset can be used for research on User Profiling, Recommender Systems, Purchase Prediction and so on. To protect the privacy of users, we have carefully encrypted the users' information. This dataset should only be used for research purpose!

# Citation:

Please cite the following paper if you use the data in any way.

1. Chen, Weijian, Yulong Gu, Zhaochun Ren, Xiangnan He, Hongtao Xie, Tong Guo, Dawei Yin, and Yongdong Zhang. "Semi-supervised User Profiling with Heterogeneous Graph Attention Networks." IJCAI 19



# Files Description:

## user:

- user_id: user id
- gender: gender of the user
- age_group: age group of the user

## user_click:

- user_id: user id
- item_id: item id
-  datatime: datetime of the click behavior
- dt: date of the click behavior

## user_order:

- user_id: user id
- item_id: item id
- count: amount of purchased item
- datetime: datetime of the order behavior
- dt: date of the order behavior

## item_info:

- item_id: item id
- cid1: first level category id of the item
- cid2: send level category id of the item of the item
-  cid3: third level category id of the item
- cid1_name: name of cid1
- cid2_name: name of cid2
- cid3_name: name of cid3
-  brand_code: brand code of the item
- price: price of the item
-  item_name: title of the item
- seg_name: segments of the item_name

