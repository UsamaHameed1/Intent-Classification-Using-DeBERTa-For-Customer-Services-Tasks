# Intent Classification Using Transformer

## _Natural Language Processing Semester Project_

## Problem Explanation

The **intent classification** problem in NLP involves predicting the intention or purpose behind a given text input, such as a user query, with the goal of providing an appropriate response or action.

## Goal

Baed on the input of the customer, our model can link predict the intent class

## Information About Dataset

## Dataset Name : **Bitext Sample Pre-built Customer Support Dataset for English**

### Dataset Explanation

This dataset contains example utterances and their corresponding intents from the Customer Support domain. The data can be used to train intent recognition models Natural Language Understanding (NLU) platforms.

The dataset covers the "Customer Support" domain and includes 27 intents grouped in 11 categories. These intents have been selected from Bitext's collection of 20 domain-specific datasets (banking, retail, utilities…), keeping the intents that are common across domains. See below for a full list of categories and intents.

## Source of Dataset

1.  Dataset hosted on Kaggle.com
2.  Bitext Sample Pre-built Customer Support Dataset for English : [Link to dataset](https://www.kaggle.com/datasets/536db59649ec509a2808c8d2c85d560c64e1dce44778a22ab79ce3408813e8fb)

## Intent Classes of the Dataset

Following are the 27 intent classes of the dataset.

```sh
The Intents in the dataset are as followed
{'cancel_order': 17,
 'change_order': 3,
 'change_shipping_address': 5,
 'check_cancellation_fee': 21,
 'check_invoices': 4,
 'check_payment_methods': 2,
 'check_refund_policy': 6,
 'complaint': 20,
 'contact_customer_service': 13,
 'contact_human_agent': 0,
 'create_account': 10,
 'delete_account': 9,
 'delivery_options': 23,
 'delivery_period': 7,
 'edit_account': 11,
 'get_invoice': 1,
 'get_refund': 16,
 'newsletter_subscription': 15,
 'payment_issue': 18,
 'place_order': 22,
 'recover_password': 8,
 'registration_problems': 25,
 'review': 26,
 'set_up_shipping_address': 19,
 'switch_account': 12,
 'track_order': 24,
 'track_refund': 14}
Total Number of Intents : 27
```

## A breif look at the dataset

```sh
{'category': 'ACCOUNT',
 'flags': 'BILC',
 'intent': 'create_account',
 'utterance': "I don't have an online account, what do I have to do to "
              'register?'}
```

| Tools and Algorithms | Name                                               |
| -------------------- | -------------------------------------------------- |
| Editor               | Google Colab                                       |
| Transformer Model    | DeBERTa [Transformer-based neural language model ] |
