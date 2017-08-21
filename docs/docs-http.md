# 



## Server Configuration for Base URLs

This section provides details on the environments available and lists down the servers in each of the environment. The default environment for this API is set to `production` while the default server is set to `AWSECommerceServicePort`.
### Environments

An environment consists of a set of servers with base URL values. The environment can be changed programatically allowing rapid switching between different environments e.g.the user can specify a Production and Testing Environment.The available environments for this API are: 

#### production
The environment comprises of the following servers: 

| Name | Base URL | 
|-----------|-------------|
| AWSECommerceServicePort | https://webservices.amazon.com/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortCA | https://webservices.amazon.ca/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortCN | https://webservices.amazon.cn/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortDE | https://webservices.amazon.de/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortES | https://webservices.amazon.es/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortFR | https://webservices.amazon.fr/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortIN | https://webservices.amazon.in/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortIT | https://webservices.amazon.it/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortJP | https://webservices.amazon.co.jp/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortUK | https://webservices.amazon.co.uk/onca/soap?Service=AWSECommerceService |
| AWSECommerceServicePortUS | https://webservices.amazon.com/onca/soap?Service=AWSECommerceService |




## Authentication
This API uses `OAuth v1.0` with `token secret`.






# <a name="api_reference"></a>API Reference

* [AWSECommerceServiceBinding](#awse_commerce_service_binding)

## <a name="awse_commerce_service_binding"></a>![Endpoint Group: ](https://apidocs.io/img/class.png "AWSECommerceServiceBinding") AWSECommerceServiceBinding


### <a name="item_search"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch") ItemSearch


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 171,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 171,
      "MerchantId": "MerchantId",
      "MinimumPrice": 171,
      "MinPercentageOff": 171,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 171
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 171,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 171,
        "MerchantId": "MerchantId",
        "MinimumPrice": 171,
        "MinPercentageOff": 171,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 171
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 129,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 129.739370827907
    }
  }
}
```


### <a name="item_lookup"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup") ItemLookup


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 129
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 129
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 129.739370827907
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 129,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup") BrowseNodeLookup


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 129.739370827907
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 129,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 129,
            "MerchantId": "MerchantId",
            "MinimumPrice": 129,
            "MinPercentageOff": 129,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 129
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 129
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 129,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 129,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 129,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": true,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup") SimilarityLookup


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 221.23465271957
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 221,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet") CartGet


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 221.23465271957
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 221,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 221,
            "MerchantId": "MerchantId",
            "MinimumPrice": 221,
            "MinPercentageOff": 221,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 221
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 221
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 221,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 221,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 221,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 221,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 221,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 221,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 221,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 221,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 221,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 221,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd") CartAdd


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 57,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 57,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 57.729934611232
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 57,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 57,
          "MerchantId": "MerchantId",
          "MinimumPrice": 57,
          "MinPercentageOff": 57,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 57
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 57
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 57,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 57,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 57,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 57,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 57,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 57,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 57,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 57,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 57,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 57,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate") CartCreate


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 248,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 248,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 207.046260606519
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 207,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 207,
          "MerchantId": "MerchantId",
          "MinimumPrice": 207,
          "MinPercentageOff": 207,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 207
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 207
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 207,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 207,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 207,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 207,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 207,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 207,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 207,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 207,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 207,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 207,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify") CartModify


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 207,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 207,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 207.046260606519
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 43,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 43,
          "MerchantId": "MerchantId",
          "MinimumPrice": 43,
          "MinPercentageOff": 43,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 43
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 43
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 43,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 43,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 43,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 43,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 43,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 43,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 43,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 43,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 43,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 43,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear") CartClear


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description




#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 43.5415424981814
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 43,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 43,
          "MerchantId": "MerchantId",
          "MinimumPrice": 43,
          "MinPercentageOff": 43,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 43
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 43
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 43,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 135,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 135,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 135,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 135,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 135,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 135,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 135,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 135,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 135,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search9"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch9") ItemSearch9


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 135,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 135,
      "MerchantId": "MerchantId",
      "MinimumPrice": 135,
      "MinPercentageOff": 135,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 135
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 135,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 135,
        "MerchantId": "MerchantId",
        "MinimumPrice": 135,
        "MinPercentageOff": 135,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 135
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 135,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 135.036824389844
    }
  }
}
```


### <a name="item_lookup10"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup10") ItemLookup10


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 135
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 135
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 135.036824389844
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 135,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup11"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup11") BrowseNodeLookup11


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 93.3136511632771
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 93,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 93,
            "MerchantId": "MerchantId",
            "MinimumPrice": 93,
            "MinPercentageOff": 93,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 93
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 93
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 93,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 93,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 93,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup12"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup12") SimilarityLookup12


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 93.3136511632771
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 93,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get13"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet13") CartGet13


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 184.808933054939
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 184,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 184,
            "MerchantId": "MerchantId",
            "MinimumPrice": 184,
            "MinPercentageOff": 184,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 184
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 184
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 184,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 184,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 184,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 184,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 184,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 184,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 184,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 184,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 184,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 184,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add14"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd14") CartAdd14


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 184,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 184,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 184.808933054939
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 184,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 184,
          "MerchantId": "MerchantId",
          "MinimumPrice": 184,
          "MinPercentageOff": 184,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 184
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 184
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 21,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 21,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 21,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 21,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 21,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 21,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 21,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 21,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 21,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 21,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create15"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate15") CartCreate15


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 21,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 21,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 21.3042149466016
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 21,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 21,
          "MerchantId": "MerchantId",
          "MinimumPrice": 21,
          "MinPercentageOff": 21,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 21
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 21
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 234,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 234,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 234,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 234,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 234,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 234,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 234,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 234,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 234,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 234,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify16"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify16") CartModify16


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 234,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 234,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 234.581041720035
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 234,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 234,
          "MerchantId": "MerchantId",
          "MinimumPrice": 234,
          "MinPercentageOff": 234,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 234
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 234
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 234,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 234,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 234,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 71,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 71,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 71,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 71,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 71,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 71,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 71,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear17"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear17") CartClear17


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCA`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 71.0763236116973
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 71,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 71,
          "MerchantId": "MerchantId",
          "MinimumPrice": 71,
          "MinPercentageOff": 71,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 71
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 71
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 71,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 71,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 71,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 71,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 71,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 71,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 29,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 29,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 29,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 29,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search18"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch18") ItemSearch18


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 29,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 29,
      "MerchantId": "MerchantId",
      "MinimumPrice": 29,
      "MinPercentageOff": 29,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 29
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 29,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 29,
        "MerchantId": "MerchantId",
        "MinimumPrice": 29,
        "MinPercentageOff": 29,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 29
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 29,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 29.3531503851307
    }
  }
}
```


### <a name="item_lookup19"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup19") ItemLookup19


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 29
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 29
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 29.3531503851307
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 29,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup20"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup20") BrowseNodeLookup20


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 29.3531503851307
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 29,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 29,
            "MerchantId": "MerchantId",
            "MinimumPrice": 29,
            "MinPercentageOff": 29,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 29
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 29
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 29,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 29,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 29,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup21"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup21") SimilarityLookup21


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 120.848432276793
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 120,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get22"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet22") CartGet22


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 120.848432276793
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 120,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 120,
            "MerchantId": "MerchantId",
            "MinimumPrice": 120,
            "MinPercentageOff": 120,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 120
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 120
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 212,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 212,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 212,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 212,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 212,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 212,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 212,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 212,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 212,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 212,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add23"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd23") CartAdd23


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 212,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 212,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 212.343714168455
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 212,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 212,
          "MerchantId": "MerchantId",
          "MinimumPrice": 212,
          "MinPercentageOff": 212,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 212
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 212
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 212,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 212,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 212,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 212,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 170,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 170,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create24"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate24") CartCreate24


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 170,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 170,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 170.620540941889
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 170,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 170,
          "MerchantId": "MerchantId",
          "MinimumPrice": 170,
          "MinPercentageOff": 170,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 170
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 170
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 170,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 170,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 170,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 170,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 170,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 170,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 7,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify25"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify25") CartModify25


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 7,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 7,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 7.11582283355101
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 7,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 7,
          "MerchantId": "MerchantId",
          "MinimumPrice": 7,
          "MinPercentageOff": 7,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 7
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 7
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 7,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 7,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 7,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 7,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 7,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 7,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 7,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 7,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 7,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 7,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear26"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear26") CartClear26


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortCN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 98.6111047252133
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 98,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 98,
          "MerchantId": "MerchantId",
          "MinimumPrice": 98,
          "MinPercentageOff": 98,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 98
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 98
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 98,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 98,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 98,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 98,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 98,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 98,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 98,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 98,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 98,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 98,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search27"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch27") ItemSearch27


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 56,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 56,
      "MerchantId": "MerchantId",
      "MinimumPrice": 56,
      "MinPercentageOff": 56,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 56
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 56,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 56,
        "MerchantId": "MerchantId",
        "MinimumPrice": 56,
        "MinPercentageOff": 56,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 56
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 56,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 56.8879314986467
    }
  }
}
```


### <a name="item_lookup28"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup28") ItemLookup28


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 56
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 56
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 56.8879314986467
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 56,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup29"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup29") BrowseNodeLookup29


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 56.8879314986467
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 56,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 56,
            "MerchantId": "MerchantId",
            "MinimumPrice": 56,
            "MinPercentageOff": 56,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 56
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 56
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 56,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 56,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 56,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": true,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup30"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup30") SimilarityLookup30


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 148.383213390309
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 148,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get31"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet31") CartGet31


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 148.383213390309
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 148,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 148,
            "MerchantId": "MerchantId",
            "MinimumPrice": 148,
            "MinPercentageOff": 148,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 148
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 148
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 148,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 148,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 148,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 148,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 148,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 148,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 148,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 106,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 106,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 106,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add32"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd32") CartAdd32


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 106,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 106,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 106.660040163742
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 106,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 106,
          "MerchantId": "MerchantId",
          "MinimumPrice": 106,
          "MinPercentageOff": 106,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 106
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 106
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 106,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 106,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 106,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 106,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 106,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 106,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 106,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 106,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 106,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 106,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create33"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate33") CartCreate33


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 198,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 198,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 198.155322055405
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 198,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 198,
          "MerchantId": "MerchantId",
          "MinimumPrice": 198,
          "MinPercentageOff": 198,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 198
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 198
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 198,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 198,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 198,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 198,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 198,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 198,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 198,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 198,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 198,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 198,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify34"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify34") CartModify34


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 34,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 34,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 34.650603947067
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 34,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 34,
          "MerchantId": "MerchantId",
          "MinimumPrice": 34,
          "MinPercentageOff": 34,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 34
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 34
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 34,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 34,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 34,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 34,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 34,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 34,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 34,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 34,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 34,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 34,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear35"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear35") CartClear35


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortDE`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 247.9274307205
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 247,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 247,
          "MerchantId": "MerchantId",
          "MinimumPrice": 247,
          "MinPercentageOff": 247,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 247
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 247
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 247,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 247,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 247,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 247,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 247,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 247,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 247,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 247,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 247,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 247,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search36"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch36") ItemSearch36


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 247,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 247,
      "MerchantId": "MerchantId",
      "MinimumPrice": 247,
      "MinPercentageOff": 247,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 247
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 247,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 247,
        "MerchantId": "MerchantId",
        "MinimumPrice": 247,
        "MinPercentageOff": 247,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 247
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 84,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 84.4227126121627
    }
  }
}
```


### <a name="item_lookup37"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup37") ItemLookup37


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 84
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 84
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 84.4227126121627
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 84,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup38"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup38") BrowseNodeLookup38


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 84.4227126121627
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 84,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 84,
            "MerchantId": "MerchantId",
            "MinimumPrice": 84,
            "MinPercentageOff": 84,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 84
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 84
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 84,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 84,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 84,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup39"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup39") SimilarityLookup39


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 175.917994503825
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 175,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get40"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet40") CartGet40


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 175.917994503825
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 175,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 175,
            "MerchantId": "MerchantId",
            "MinimumPrice": 175,
            "MinPercentageOff": 175,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 175
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 175
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 175,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 175,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 175,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 175,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 175,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 175,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 175,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 175,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 175,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 175,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add41"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd41") CartAdd41


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 134,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 134,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 134.194821277258
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 134,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 134,
          "MerchantId": "MerchantId",
          "MinimumPrice": 134,
          "MinPercentageOff": 134,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 134
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 134
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 134,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 134,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 134,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 134,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 134,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 134,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 134,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 134,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 134,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 134,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create42"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate42") CartCreate42


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 134,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 134,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 225.690103168921
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 225,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 225,
          "MerchantId": "MerchantId",
          "MinimumPrice": 225,
          "MinPercentageOff": 225,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 225
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 225
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 225,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 225,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 225,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 225,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 225,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 225,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 225,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 225,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 225,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 225,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify43"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify43") CartModify43


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 225,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 225,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 225.690103168921
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 225,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 225,
          "MerchantId": "MerchantId",
          "MinimumPrice": 225,
          "MinPercentageOff": 225,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 225
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 183
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 183,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 183,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 183,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 183,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 183,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 183,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 183,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 183,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 183,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 183,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear44"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear44") CartClear44


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortES`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 183.966929942354
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 183,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 183,
          "MerchantId": "MerchantId",
          "MinimumPrice": 183,
          "MinPercentageOff": 183,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 183
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 183
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 183,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 183,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 183,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 20,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 20,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 20,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 20,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 20,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 20,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 20,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search45"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch45") ItemSearch45


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 111,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 111,
      "MerchantId": "MerchantId",
      "MinimumPrice": 111,
      "MinPercentageOff": 111,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 111
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 111,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 111,
        "MerchantId": "MerchantId",
        "MinimumPrice": 111,
        "MinPercentageOff": 111,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 111
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 111,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 70.234320499112
    }
  }
}
```


### <a name="item_lookup46"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup46") ItemLookup46


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 70
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 70
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 70.234320499112
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 70,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup47"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup47") BrowseNodeLookup47


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 70.234320499112
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 70,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 70,
            "MerchantId": "MerchantId",
            "MinimumPrice": 70,
            "MinPercentageOff": 70,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 70
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 70
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 70,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 70,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 70,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup48"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup48") SimilarityLookup48


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 161.729602390774
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 161,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get49"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet49") CartGet49


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 161.729602390774
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 161,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 161,
            "MerchantId": "MerchantId",
            "MinimumPrice": 161,
            "MinPercentageOff": 161,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 161
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 161
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 161,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 161,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 161,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 161,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 161,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 161,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 161,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 161,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 161,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 161,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add50"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd50") CartAdd50


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 161,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 161,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 253.224884282437
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 253,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 253,
          "MerchantId": "MerchantId",
          "MinimumPrice": 253,
          "MinPercentageOff": 253,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 253
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 253
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 253,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 253,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 253,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 253,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 253,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 253,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 253,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 253,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 253,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 253,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create51"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate51") CartCreate51


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 253,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 253,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 253.224884282437
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 211,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 211,
          "MerchantId": "MerchantId",
          "MinimumPrice": 211,
          "MinPercentageOff": 211,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 211
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 211
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 211,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 211,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 211,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 211,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 211,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 211,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 211,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 211,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 211,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 211,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify52"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify52") CartModify52


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 211,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 211,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 211.50171105587
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 211,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 211,
          "MerchantId": "MerchantId",
          "MinimumPrice": 211,
          "MinPercentageOff": 211,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 211
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 47
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 47,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 47,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 47,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear53"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear53") CartClear53


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortFR`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 47.9969929475323
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 47,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 47,
          "MerchantId": "MerchantId",
          "MinimumPrice": 47,
          "MinPercentageOff": 47,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 47
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 47
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 6,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 6,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 6,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 6,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 6,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 6,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 6,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search54"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch54") ItemSearch54


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 6,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 6,
      "MerchantId": "MerchantId",
      "MinimumPrice": 6,
      "MinPercentageOff": 6,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 6
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 6,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 6,
        "MerchantId": "MerchantId",
        "MinimumPrice": 6,
        "MinPercentageOff": 6,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 6
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 6,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 6.27381972096573
    }
  }
}
```


### <a name="item_lookup55"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup55") ItemLookup55


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 6
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 6
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 6.27381972096573
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 6,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup56"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup56") BrowseNodeLookup56


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 97.769101612628
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 97,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 97,
            "MerchantId": "MerchantId",
            "MinimumPrice": 97,
            "MinPercentageOff": 97,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 97
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 97
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 97,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 97,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 97,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup57"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup57") SimilarityLookup57


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 97.769101612628
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 97,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get58"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet58") CartGet58


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 97.769101612628
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 97,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 97,
            "MerchantId": "MerchantId",
            "MinimumPrice": 97,
            "MinPercentageOff": 97,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 97
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 189
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 189,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 189,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 189,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 189,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 189,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 189,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 189,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 33,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 33,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 33,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add59"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd59") CartAdd59


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 33,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 33,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 33.8086008344817
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 33,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 33,
          "MerchantId": "MerchantId",
          "MinimumPrice": 33,
          "MinPercentageOff": 33,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 33
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 33
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 33,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 33,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 33,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 33,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 33,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 33,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 33,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 33,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 33,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 33,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create60"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate60") CartCreate60


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 125,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 125,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 125.303882726144
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 125,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 125,
          "MerchantId": "MerchantId",
          "MinimumPrice": 125,
          "MinPercentageOff": 125,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 125
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 125
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 125,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 125,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 125,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 125,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 125,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 125,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 125,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 125,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 125,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 125,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify61"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify61") CartModify61


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 83,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 83,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 83.5807094995774
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 83,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 83,
          "MerchantId": "MerchantId",
          "MinimumPrice": 83,
          "MinPercentageOff": 83,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 83
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 83
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 83,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 83,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 83,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 83,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 83,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 83,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 83,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 83,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 83,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 83,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear62"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear62") CartClear62


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIN`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 175.07599139124
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 175,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 175,
          "MerchantId": "MerchantId",
          "MinimumPrice": 175,
          "MinPercentageOff": 175,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 175
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 175
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 175,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 175,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 175,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 175,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 175,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 175,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 175,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 175,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 175,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 175,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search63"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch63") ItemSearch63


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 175,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 175,
      "MerchantId": "MerchantId",
      "MinimumPrice": 175,
      "MinPercentageOff": 175,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 175
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 175,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 175,
        "MerchantId": "MerchantId",
        "MinimumPrice": 175,
        "MinPercentageOff": 175,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 11
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 252,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 252.382881169851
    }
  }
}
```


### <a name="item_lookup64"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup64") ItemLookup64


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 252
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 252
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 252.382881169851
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 252,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup65"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup65") BrowseNodeLookup65


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 252.382881169851
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 252,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 252,
            "MerchantId": "MerchantId",
            "MinimumPrice": 252,
            "MinPercentageOff": 252,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 252
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 252
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 252,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 252,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 252,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup66"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup66") SimilarityLookup66


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 88.8781630615136
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 88,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get67"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet67") CartGet67


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 88.8781630615136
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 88,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 88,
            "MerchantId": "MerchantId",
            "MinimumPrice": 88,
            "MinPercentageOff": 88,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 88
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 88
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 88,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 88,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 88,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 88,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 88,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 88,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 88,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 47,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 47,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 47,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add68"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd68") CartAdd68


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 47,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 47,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 47.154989834947
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 47,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 47,
          "MerchantId": "MerchantId",
          "MinimumPrice": 47,
          "MinPercentageOff": 47,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 47
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 47
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 47,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 47,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 47,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 47,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 47,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create69"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate69") CartCreate69


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 138,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 138,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 138.650271726609
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 138,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 138,
          "MerchantId": "MerchantId",
          "MinimumPrice": 138,
          "MinPercentageOff": 138,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 138
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 138
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 138,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 138,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 138,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 138,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 138,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 138,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 138,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 138,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 138,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 138,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify70"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify70") CartModify70


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 230,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 230,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 230.145553618272
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 230,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 230,
          "MerchantId": "MerchantId",
          "MinimumPrice": 230,
          "MinPercentageOff": 230,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 230
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 230
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 230,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 230,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 230,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 230,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 230,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 230,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 230,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 230,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 230,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 230,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear71"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear71") CartClear71


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortIT`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 188.422380391705
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 188,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 188,
          "MerchantId": "MerchantId",
          "MinimumPrice": 188,
          "MinPercentageOff": 188,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 188
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 188
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 188,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 188,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 188,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 188,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 188,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 188,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 188,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 188,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 188,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 188,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search72"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch72") ItemSearch72


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 24,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 24,
      "MerchantId": "MerchantId",
      "MinimumPrice": 24,
      "MinPercentageOff": 24,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 24
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 24,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 24,
        "MerchantId": "MerchantId",
        "MinimumPrice": 24,
        "MinPercentageOff": 24,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 24
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 24,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 24.9176622833673
    }
  }
}
```


### <a name="item_lookup73"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup73") ItemLookup73


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 24
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 24
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 24.9176622833673
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 24,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup74"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup74") BrowseNodeLookup74


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 24.9176622833673
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 24,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 24,
            "MerchantId": "MerchantId",
            "MinimumPrice": 24,
            "MinPercentageOff": 24,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 24
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 24
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 24,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 24,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 24,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup75"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup75") SimilarityLookup75


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 238.194489056801
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 238,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get76"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet76") CartGet76


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 238.194489056801
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 238,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 238,
            "MerchantId": "MerchantId",
            "MinimumPrice": 238,
            "MinPercentageOff": 238,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 238
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 238
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 238,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 238,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 238,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 238,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 238,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 238,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 238,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 238,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 238,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 238,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add77"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd77") CartAdd77


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 74,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 74,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 74.689770948463
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 74,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 74,
          "MerchantId": "MerchantId",
          "MinimumPrice": 74,
          "MinPercentageOff": 74,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 74
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 74
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 74,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 74,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 74,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 74,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 74,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 74,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 74,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 74,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 74,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 74,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create78"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate78") CartCreate78


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 166,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 166,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 166.185052840125
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 166,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 166,
          "MerchantId": "MerchantId",
          "MinimumPrice": 166,
          "MinPercentageOff": 166,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 166
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 166
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 166,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 166,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 166,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 166,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 166,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 166,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 166,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 166,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 166,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 166,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify79"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify79") CartModify79


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 10,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 10,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 10.7292701703167
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 102,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 102,
          "MerchantId": "MerchantId",
          "MinimumPrice": 102,
          "MinPercentageOff": 102,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 102
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 102
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 102,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 102,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 102,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 102,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 102,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 102,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 102,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 102,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 102,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 102,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear80"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear80") CartClear80


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortJP`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 102.224552061979
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 102,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 102,
          "MerchantId": "MerchantId",
          "MinimumPrice": 102,
          "MinPercentageOff": 102,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 102
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 102
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 102,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 60,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 60,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 60,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 60,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 60,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 60,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 60,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 60,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 60,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search81"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch81") ItemSearch81


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 60,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 60,
      "MerchantId": "MerchantId",
      "MinimumPrice": 60,
      "MinPercentageOff": 60,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 60
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 60,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 60,
        "MerchantId": "MerchantId",
        "MinimumPrice": 60,
        "MinPercentageOff": 60,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 60
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 60,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 60.5013788354124
    }
  }
}
```


### <a name="item_lookup82"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup82") ItemLookup82


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 60
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 60
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 60.5013788354124
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 151,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup83"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup83") BrowseNodeLookup83


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 151.996660727075
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 151,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 151,
            "MerchantId": "MerchantId",
            "MinimumPrice": 151,
            "MinPercentageOff": 151,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 151
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 151
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 151,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 151,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 151,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": true,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup84"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup84") SimilarityLookup84


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 151.996660727075
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 151,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get85"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet85") CartGet85


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 243.491942618737
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 243,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 243,
            "MerchantId": "MerchantId",
            "MinimumPrice": 243,
            "MinPercentageOff": 243,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 243
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 243
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 243,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 243,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 243,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 243,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 243,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 243,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 243,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 243,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 243,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 243,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add86"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd86") CartAdd86


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 243,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 243,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 243.491942618737
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 201,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 201,
          "MerchantId": "MerchantId",
          "MinimumPrice": 201,
          "MinPercentageOff": 201,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 201
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 201
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 201,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 201,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 201,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 201,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 179,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 137,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 137,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 137,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 137,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 137,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create87"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate87") CartCreate87


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 137,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 137,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 137.808268614024
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 137,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 137,
          "MerchantId": "MerchantId",
          "MinimumPrice": 137,
          "MinPercentageOff": 137,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 137
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 137
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 137,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 137,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 137,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 137,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 137,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 137,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 137,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 137,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 137,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 137,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify88"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify88") CartModify88


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 165,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 165,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 165.34304972754
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 165,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 165,
          "MerchantId": "MerchantId",
          "MinimumPrice": 165,
          "MinPercentageOff": 165,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 165
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 165
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 165,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 165,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 165,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 1,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 1,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 1,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 1,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 1,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 1,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 1,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear89"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear89") CartClear89


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUK`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 1.83833161920231
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 1,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 1,
          "MerchantId": "MerchantId",
          "MinimumPrice": 1,
          "MinPercentageOff": 1,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 1
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 1
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 1,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 1,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 1,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 1,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 1,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 1,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 215,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 215,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 215,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 215,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="item_search90"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemSearch90") ItemSearch90


**`POST`** `/ItemSearch`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemSearchRequestMsg](#item_search_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "XMLEscaping": "XMLEscaping",
    "Validate": "Validate",
    "Shared": {
      "Availability": "Available",
      "Actor": "Actor",
      "Artist": "Artist",
      "AudienceRating": [
        "G"
      ],
      "Author": "Author",
      "Brand": "Brand",
      "BrowseNode": "BrowseNode",
      "Composer": "Composer",
      "Condition": "All",
      "Conductor": "Conductor",
      "Director": "Director",
      "ItemPage": 215,
      "Keywords": "Keywords",
      "Manufacturer": "Manufacturer",
      "MaximumPrice": 215,
      "MerchantId": "MerchantId",
      "MinimumPrice": 215,
      "MinPercentageOff": 215,
      "MusicLabel": "MusicLabel",
      "Orchestra": "Orchestra",
      "Power": "Power",
      "Publisher": "Publisher",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "Sort": "Sort",
      "Title": "Title",
      "ReleaseDate": "ReleaseDate",
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 215
    },
    "Request": [
      {
        "Availability": "Available",
        "Actor": "Actor",
        "Artist": "Artist",
        "AudienceRating": [
          "G"
        ],
        "Author": "Author",
        "Brand": "Brand",
        "BrowseNode": "BrowseNode",
        "Composer": "Composer",
        "Condition": "All",
        "Conductor": "Conductor",
        "Director": "Director",
        "ItemPage": 215,
        "Keywords": "Keywords",
        "Manufacturer": "Manufacturer",
        "MaximumPrice": 215,
        "MerchantId": "MerchantId",
        "MinimumPrice": 215,
        "MinPercentageOff": 215,
        "MusicLabel": "MusicLabel",
        "Orchestra": "Orchestra",
        "Power": "Power",
        "Publisher": "Publisher",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "Sort": "Sort",
        "Title": "Title",
        "ReleaseDate": "ReleaseDate",
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 215
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemSearchResponseMsg](#item_search_response_msg)) 
```
{
  "body": {
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 215,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    },
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 215.115158392636
    }
  }
}
```


### <a name="item_lookup91"></a>![Endpoint: ](https://apidocs.io/img/method.png "ItemLookup91") ItemLookup91


**`POST`** `/ItemLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [ItemLookupRequestMsg](#item_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "IdType": "ASIN",
      "MerchantId": "MerchantId",
      "ItemId": [
        "ItemId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ],
      "SearchIndex": "SearchIndex",
      "VariationPage": "VariationPage",
      "RelatedItemPage": "RelatedItemPage",
      "RelationshipType": [
        "RelationshipType"
      ],
      "IncludeReviewsSummary": "IncludeReviewsSummary",
      "TruncateReviewsAt": 215
    },
    "Request": [
      {
        "Condition": "All",
        "IdType": "ASIN",
        "MerchantId": "MerchantId",
        "ItemId": [
          "ItemId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ],
        "SearchIndex": "SearchIndex",
        "VariationPage": "VariationPage",
        "RelatedItemPage": "RelatedItemPage",
        "RelationshipType": [
          "RelationshipType"
        ],
        "IncludeReviewsSummary": "IncludeReviewsSummary",
        "TruncateReviewsAt": 215
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([ItemLookupResponseMsg](#item_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 215.115158392636
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 101,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="browse_node_lookup92"></a>![Endpoint: ](https://apidocs.io/img/method.png "BrowseNodeLookup92") BrowseNodeLookup92


**`POST`** `/BrowseNodeLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [BrowseNodeLookupRequestMsg](#browse_node_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "BrowseNodeId": [
        "BrowseNodeId"
      ],
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "BrowseNodeId": [
          "BrowseNodeId"
        ],
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([BrowseNodeLookupResponseMsg](#browse_node_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 101.382548949394
    },
    "BrowseNodes": [
      {
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 101,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 101,
            "MerchantId": "MerchantId",
            "MinimumPrice": 101,
            "MinPercentageOff": 101,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 101
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 101
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 101,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 101,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 101,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "BrowseNode": [
          {
            "Properties": {
              "Property": [
                {
                  "Name": "Name",
                  "Value": "Value"
                }
              ]
            },
            "Children": {
              "BrowseNode": []
            },
            "Ancestors": {
              "BrowseNode": []
            },
            "TopSellers": {
              "TopSeller": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "NewReleases": {
              "NewRelease": {
                "ASIN": "ASIN",
                "Title": "Title"
              }
            },
            "BrowseNodeId": "BrowseNodeId",
            "Name": "Name",
            "IsCategoryRoot": false,
            "TopItemSet": [
              {
                "TopItem": {
                  "ASIN": "ASIN",
                  "Title": "Title",
                  "DetailPageURL": "DetailPageURL",
                  "ProductGroup": "ProductGroup",
                  "Author": [
                    "Author"
                  ],
                  "Artist": [
                    "Artist"
                  ],
                  "Actor": [
                    "Actor"
                  ]
                },
                "Type": "Type"
              }
            ]
          }
        ]
      }
    ]
  }
}
```


### <a name="similarity_lookup93"></a>![Endpoint: ](https://apidocs.io/img/method.png "SimilarityLookup93") SimilarityLookup93


**`POST`** `/SimilarityLookup`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [SimilarityLookupRequestMsg](#similarity_lookup_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Condition": "All",
      "SimilarityType": "Intersection",
      "ItemId": [
        "ItemId"
      ],
      "MerchantId": "MerchantId",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Condition": "All",
        "SimilarityType": "Intersection",
        "ItemId": [
          "ItemId"
        ],
        "MerchantId": "MerchantId",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([SimilarityLookupResponseMsg](#similarity_lookup_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 192.877830841056
    },
    "Items": {
      "Item": {
        "ASIN": "ASIN",
        "OfferListingId": "OfferListingId",
        "Quantity": 192,
        "AssociateTag": "AssociateTag",
        "ListItemId": "ListItemId"
      }
    }
  }
}
```


### <a name="cart_get94"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartGet94") CartGet94


**`POST`** `/CartGet`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartGetRequestMsg](#cart_get_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartGetResponseMsg](#cart_get_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 192.877830841056
    },
    "Cart": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "URLEncodedHMAC": "URLEncodedHMAC",
        "Request": {
          "BrowseNodeLookupRequest": {
            "BrowseNodeId": [
              "BrowseNodeId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "ItemSearchRequest": {
            "Availability": "Available",
            "Actor": "Actor",
            "Artist": "Artist",
            "AudienceRating": [
              "G"
            ],
            "Author": "Author",
            "Brand": "Brand",
            "BrowseNode": "BrowseNode",
            "Composer": "Composer",
            "Condition": "All",
            "Conductor": "Conductor",
            "Director": "Director",
            "ItemPage": 192,
            "Keywords": "Keywords",
            "Manufacturer": "Manufacturer",
            "MaximumPrice": 192,
            "MerchantId": "MerchantId",
            "MinimumPrice": 192,
            "MinPercentageOff": 192,
            "MusicLabel": "MusicLabel",
            "Orchestra": "Orchestra",
            "Power": "Power",
            "Publisher": "Publisher",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "Sort": "Sort",
            "Title": "Title",
            "ReleaseDate": "ReleaseDate",
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 192
          },
          "ItemLookupRequest": {
            "Condition": "All",
            "IdType": "ASIN",
            "MerchantId": "MerchantId",
            "ItemId": [
              "ItemId"
            ],
            "ResponseGroup": [
              "ResponseGroup"
            ],
            "SearchIndex": "SearchIndex",
            "VariationPage": "VariationPage",
            "RelatedItemPage": "RelatedItemPage",
            "RelationshipType": [
              "RelationshipType"
            ],
            "IncludeReviewsSummary": "IncludeReviewsSummary",
            "TruncateReviewsAt": 192
          },
          "SimilarityLookupRequest": {
            "Condition": "All",
            "SimilarityType": "Intersection",
            "ItemId": [
              "ItemId"
            ],
            "MerchantId": "MerchantId",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartGetRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartAddRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 29,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartCreateRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 29,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartModifyRequest": {
            "Items": {
              "Item": {
                "ASIN": "ASIN",
                "OfferListingId": "OfferListingId",
                "Quantity": 29,
                "AssociateTag": "AssociateTag",
                "ListItemId": "ListItemId"
              }
            },
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "CartClearRequest": {
            "CartId": "CartId",
            "HMAC": "HMAC",
            "MergeCart": "MergeCart",
            "ResponseGroup": [
              "ResponseGroup"
            ]
          },
          "Errors": {
            "Error": {
              "Code": "Code",
              "Message": "Message"
            }
          },
          "IsValid": "IsValid"
        },
        "PurchaseURL": "PurchaseURL",
        "MobileCartURL": "MobileCartURL",
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 29,
          "CurrencyCode": "CurrencyCode"
        },
        "CartItems": {
          "CartItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 29,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 29,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 29,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SavedForLaterItems": {
          "SavedForLaterItem": [
            {
              "CartItemId": "CartItemId",
              "Quantity": "Quantity",
              "MetaData": {
                "KeyValuePair": {
                  "Key": "Key",
                  "Value": "Value"
                }
              },
              "Price": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 29,
                "CurrencyCode": "CurrencyCode"
              },
              "ASIN": "ASIN",
              "SellerNickname": "SellerNickname",
              "Title": "Title",
              "ProductGroup": "ProductGroup",
              "ItemTotal": {
                "FormattedPrice": "FormattedPrice",
                "Amount": 29,
                "CurrencyCode": "CurrencyCode"
              }
            }
          ],
          "SubTotal": {
            "FormattedPrice": "FormattedPrice",
            "Amount": 29,
            "CurrencyCode": "CurrencyCode"
          }
        },
        "SimilarProducts": {
          "SimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "TopSellers": {
          "TopSeller": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "NewReleases": {
          "NewRelease": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "SimilarViewedProducts": {
          "SimilarViewedProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        },
        "OtherCategoriesSimilarProducts": {
          "OtherCategoriesSimilarProduct": {
            "ASIN": "ASIN",
            "Title": "Title"
          }
        }
      }
    ]
  }
}
```


### <a name="cart_add95"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartAdd95") CartAdd95


**`POST`** `/CartAdd`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartAddRequestMsg](#cart_add_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 29,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 29,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartAddResponseMsg](#cart_add_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 29.3731127327183
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 242,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 242,
          "MerchantId": "MerchantId",
          "MinimumPrice": 242,
          "MinPercentageOff": 242,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 242
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 242
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 242,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 242,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 242,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 242,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 242,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 242,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 242,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 79,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 79,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 79,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_create96"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartCreate96") CartCreate96


**`POST`** `/CartCreate`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartCreateRequestMsg](#cart_create_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 79,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 79,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartCreateResponseMsg](#cart_create_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 79.145221397814
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 79,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 79,
          "MerchantId": "MerchantId",
          "MinimumPrice": 79,
          "MinPercentageOff": 79,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 79
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 79
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 79,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 79,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 79,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 37,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 37,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 37,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_modify97"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartModify97") CartModify97


**`POST`** `/CartModify`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartModifyRequestMsg](#cart_modify_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "Items": {
        "Item": {
          "ASIN": "ASIN",
          "OfferListingId": "OfferListingId",
          "Quantity": 37,
          "AssociateTag": "AssociateTag",
          "ListItemId": "ListItemId"
        }
      },
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "Items": {
          "Item": {
            "ASIN": "ASIN",
            "OfferListingId": "OfferListingId",
            "Quantity": 37,
            "AssociateTag": "AssociateTag",
            "ListItemId": "ListItemId"
          }
        },
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartModifyResponseMsg](#cart_modify_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 37.4220481712474
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 37,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 37,
          "MerchantId": "MerchantId",
          "MinimumPrice": 37,
          "MinPercentageOff": 37,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 37
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 37
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 37,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 37,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 37,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 37,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 37,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 37,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 37,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


### <a name="cart_clear98"></a>![Endpoint: ](https://apidocs.io/img/method.png "CartClear98") CartClear98


**`POST`** `/CartClear`

> *Tags:*  ``` Skips Authentication ``` 

> TODO: Add a method description


#### Base URL
This endpoint uses server `AWSECommerceServicePortUS`.


#### Request Headers
>Accept=application/json;
>Content-Type=application/json;

#### Request Body
Raw 

|  Type | Tags | Description |
| ------| ---- |-------------| 
| [CartClearRequestMsg](#cart_clear_request_msg) |  ``` Required ```  | TODO: Add description | 

 Example 
``` 
{
  "body": {
    "MarketplaceDomain": "MarketplaceDomain",
    "AWSAccessKeyId": "AWSAccessKeyId",
    "AssociateTag": "AssociateTag",
    "Validate": "Validate",
    "XMLEscaping": "XMLEscaping",
    "Shared": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "MergeCart": "MergeCart",
      "ResponseGroup": [
        "ResponseGroup"
      ]
    },
    "Request": [
      {
        "CartId": "CartId",
        "HMAC": "HMAC",
        "MergeCart": "MergeCart",
        "ResponseGroup": [
          "ResponseGroup"
        ]
      }
    ]
  }
}
``` 

#### Responses
**200** 


Body ([CartClearResponseMsg](#cart_clear_response_msg)) 
```
{
  "body": {
    "OperationRequest": {
      "HTTPHeaders": {
        "Header": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "RequestId": "RequestId",
      "Arguments": {
        "Argument": {
          "Name": "Name",
          "Value": "Value"
        }
      },
      "Errors": {
        "Error": {
          "Code": "Code",
          "Message": "Message"
        }
      },
      "RequestProcessingTime": 128.91733006291
    },
    "Cart": {
      "CartId": "CartId",
      "HMAC": "HMAC",
      "URLEncodedHMAC": "URLEncodedHMAC",
      "Request": {
        "BrowseNodeLookupRequest": {
          "BrowseNodeId": [
            "BrowseNodeId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "ItemSearchRequest": {
          "Availability": "Available",
          "Actor": "Actor",
          "Artist": "Artist",
          "AudienceRating": [
            "G"
          ],
          "Author": "Author",
          "Brand": "Brand",
          "BrowseNode": "BrowseNode",
          "Composer": "Composer",
          "Condition": "All",
          "Conductor": "Conductor",
          "Director": "Director",
          "ItemPage": 128,
          "Keywords": "Keywords",
          "Manufacturer": "Manufacturer",
          "MaximumPrice": 128,
          "MerchantId": "MerchantId",
          "MinimumPrice": 128,
          "MinPercentageOff": 128,
          "MusicLabel": "MusicLabel",
          "Orchestra": "Orchestra",
          "Power": "Power",
          "Publisher": "Publisher",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "Sort": "Sort",
          "Title": "Title",
          "ReleaseDate": "ReleaseDate",
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 128
        },
        "ItemLookupRequest": {
          "Condition": "All",
          "IdType": "ASIN",
          "MerchantId": "MerchantId",
          "ItemId": [
            "ItemId"
          ],
          "ResponseGroup": [
            "ResponseGroup"
          ],
          "SearchIndex": "SearchIndex",
          "VariationPage": "VariationPage",
          "RelatedItemPage": "RelatedItemPage",
          "RelationshipType": [
            "RelationshipType"
          ],
          "IncludeReviewsSummary": "IncludeReviewsSummary",
          "TruncateReviewsAt": 128
        },
        "SimilarityLookupRequest": {
          "Condition": "All",
          "SimilarityType": "Intersection",
          "ItemId": [
            "ItemId"
          ],
          "MerchantId": "MerchantId",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartGetRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartAddRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 128,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartCreateRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 128,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartModifyRequest": {
          "Items": {
            "Item": {
              "ASIN": "ASIN",
              "OfferListingId": "OfferListingId",
              "Quantity": 128,
              "AssociateTag": "AssociateTag",
              "ListItemId": "ListItemId"
            }
          },
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "CartClearRequest": {
          "CartId": "CartId",
          "HMAC": "HMAC",
          "MergeCart": "MergeCart",
          "ResponseGroup": [
            "ResponseGroup"
          ]
        },
        "Errors": {
          "Error": {
            "Code": "Code",
            "Message": "Message"
          }
        },
        "IsValid": "IsValid"
      },
      "PurchaseURL": "PurchaseURL",
      "MobileCartURL": "MobileCartURL",
      "SubTotal": {
        "FormattedPrice": "FormattedPrice",
        "Amount": 128,
        "CurrencyCode": "CurrencyCode"
      },
      "CartItems": {
        "CartItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 128,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 128,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 128,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SavedForLaterItems": {
        "SavedForLaterItem": [
          {
            "CartItemId": "CartItemId",
            "Quantity": "Quantity",
            "MetaData": {
              "KeyValuePair": {
                "Key": "Key",
                "Value": "Value"
              }
            },
            "Price": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 128,
              "CurrencyCode": "CurrencyCode"
            },
            "ASIN": "ASIN",
            "SellerNickname": "SellerNickname",
            "Title": "Title",
            "ProductGroup": "ProductGroup",
            "ItemTotal": {
              "FormattedPrice": "FormattedPrice",
              "Amount": 128,
              "CurrencyCode": "CurrencyCode"
            }
          }
        ],
        "SubTotal": {
          "FormattedPrice": "FormattedPrice",
          "Amount": 128,
          "CurrencyCode": "CurrencyCode"
        }
      },
      "SimilarProducts": {
        "SimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "TopSellers": {
        "TopSeller": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "NewReleases": {
        "NewRelease": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "SimilarViewedProducts": {
        "SimilarViewedProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      },
      "OtherCategoriesSimilarProducts": {
        "OtherCategoriesSimilarProduct": {
          "ASIN": "ASIN",
          "Title": "Title"
        }
      }
    }
  }
}
```


[Back to API Reference](#api_reference)

## <a name="api_types"></a>![Models: ](https://apidocs.io/img/class.png "API Types") API Types

This section provides details on the available types. The primitive types available are:

| Type | Example |
| ---- | -------- |
| **string** | `hello world` |
| **boolean** |	`true` |
| **number** | `1` |
| **precision** | `1.5` |
| **datetime** | `2016-03-13T12:52:32.123Z` |
| **date** | `2016-03-13` |
|**void** | |
| **dynamic** | |
| **binary** | |
| **long** | `12345678910` |
| **file** | |
| **uuid** | `0f8fad5b-d9cb-469f-a165-70867728950e` |


In addition to the above types, the following complex types are also available:
### <a name="bin_parameter"></a>![Model: ](https://apidocs.io/img/method.png "BinParameter") BinParameter



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Name | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Value | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="bin"></a>![Model: ](https://apidocs.io/img/method.png "Bin") Bin



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| BinName | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| BinItemCount | [number](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| BinParameter | [BinParameter](#bin_parameter) |  ``` Required ```  | TODO: Add a property description | 




### <a name="search_bin_set"></a>![Model: ](https://apidocs.io/img/method.png "SearchBinSet") SearchBinSet



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| NarrowBy | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Bin | [Bin](#bin) |  ``` Required ```  | TODO: Add a property description | 




### <a name="search_bin_sets"></a>![Model: ](https://apidocs.io/img/method.png "SearchBinSets") SearchBinSets



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| SearchBinSet | [SearchBinSet](#search_bin_set) |  ``` Required ```  | TODO: Add a property description | 




### <a name="availability"></a>![Model: ](https://apidocs.io/img/method.png "Availability") Availability



> TODO: Add a method description




This type must take a value from the following [string](#api_types) enumeration of values:

| Value | Description |
| ----- | --------------- |
| `Available` | TODO: Add description | 




### <a name="audience_rating"></a>![Model: ](https://apidocs.io/img/method.png "AudienceRating") AudienceRating



> TODO: Add a method description




This type must take a value from the following [string](#api_types) enumeration of values:

| Value | Description |
| ----- | --------------- |
| `G` | TODO: Add description | 
| `PG` | TODO: Add description | 
| `PG-13` | TODO: Add description | 
| `R` | TODO: Add description | 
| `NC-17` | TODO: Add description | 
| `NR` | TODO: Add description | 
| `Unrated` | TODO: Add description | 
| `6` | TODO: Add description | 
| `12` | TODO: Add description | 
| `16` | TODO: Add description | 
| `18` | TODO: Add description | 
| `FamilyViewing` | TODO: Add description | 




### <a name="condition"></a>![Model: ](https://apidocs.io/img/method.png "Condition") Condition



> TODO: Add a method description




This type must take a value from the following [string](#api_types) enumeration of values:

| Value | Description |
| ----- | --------------- |
| `All` | TODO: Add description | 
| `New` | TODO: Add description | 
| `Used` | TODO: Add description | 
| `Collectible` | TODO: Add description | 
| `Refurbished` | TODO: Add description | 




### <a name="item_search_request"></a>![Model: ](https://apidocs.io/img/method.png "ItemSearchRequest") ItemSearchRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Availability | [Availability](#availability) |  ``` Required ```  | TODO: Add a property description | 
| Actor | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Artist | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AudienceRating | [AudienceRating](#audience_rating) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Author | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Brand | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| BrowseNode | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Composer | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Condition | [Condition](#condition) |  ``` Optional ```  | TODO: Add a property description | 
| Conductor | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Director | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ItemPage | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Keywords | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Manufacturer | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MaximumPrice | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MerchantId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MinimumPrice | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MinPercentageOff | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MusicLabel | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Orchestra | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Power | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Publisher | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelatedItemPage | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelationshipType | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| SearchIndex | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Sort | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ReleaseDate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IncludeReviewsSummary | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TruncateReviewsAt | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="item_search"></a>![Model: ](https://apidocs.io/img/method.png "ItemSearch") ItemSearch



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [ItemSearchRequest](#item_search_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [ItemSearchRequest](#item_search_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="id_type"></a>![Model: ](https://apidocs.io/img/method.png "IdType") IdType



> TODO: Add a method description




This type must take a value from the following [string](#api_types) enumeration of values:

| Value | Description |
| ----- | --------------- |
| `ASIN` | TODO: Add description | 
| `UPC` | TODO: Add description | 
| `SKU` | TODO: Add description | 
| `EAN` | TODO: Add description | 
| `ISBN` | TODO: Add description | 




### <a name="item_lookup_request"></a>![Model: ](https://apidocs.io/img/method.png "ItemLookupRequest") ItemLookupRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Condition | [Condition](#condition) |  ``` Required ```  | TODO: Add a property description | 
| IdType | [IdType](#id_type) |  ``` Required ```  | TODO: Add a property description | 
| MerchantId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ItemId | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| SearchIndex | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| VariationPage | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelatedItemPage | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelationshipType | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| IncludeReviewsSummary | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TruncateReviewsAt | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="item_lookup"></a>![Model: ](https://apidocs.io/img/method.png "ItemLookup") ItemLookup



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [ItemLookupRequest](#item_lookup_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [ItemLookupRequest](#item_lookup_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="similarity_type"></a>![Model: ](https://apidocs.io/img/method.png "SimilarityType") SimilarityType



> TODO: Add a method description




This type must take a value from the following [string](#api_types) enumeration of values:

| Value | Description |
| ----- | --------------- |
| `Intersection` | TODO: Add description | 
| `Random` | TODO: Add description | 




### <a name="similarity_lookup_request"></a>![Model: ](https://apidocs.io/img/method.png "SimilarityLookupRequest") SimilarityLookupRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Condition | [Condition](#condition) |  ``` Required ```  | TODO: Add a property description | 
| SimilarityType | [SimilarityType](#similarity_type) |  ``` Required ```  | TODO: Add a property description | 
| ItemId | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| MerchantId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="similarity_lookup"></a>![Model: ](https://apidocs.io/img/method.png "SimilarityLookup") SimilarityLookup



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [SimilarityLookupRequest](#similarity_lookup_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [SimilarityLookupRequest](#similarity_lookup_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_get_request"></a>![Model: ](https://apidocs.io/img/method.png "CartGetRequest") CartGetRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| CartId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| HMAC | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MergeCart | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_get"></a>![Model: ](https://apidocs.io/img/method.png "CartGet") CartGet



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [CartGetRequest](#cart_get_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [CartGetRequest](#cart_get_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="item"></a>![Model: ](https://apidocs.io/img/method.png "Item") Item



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| OfferListingId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Quantity | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ListItemId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="items"></a>![Model: ](https://apidocs.io/img/method.png "Items") Items



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Item | [Item](#item) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_add_request"></a>![Model: ](https://apidocs.io/img/method.png "CartAddRequest") CartAddRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Items | [Items](#items) |  ``` Required ```  | TODO: Add a property description | 
| CartId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| HMAC | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MergeCart | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_add"></a>![Model: ](https://apidocs.io/img/method.png "CartAdd") CartAdd



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [CartAddRequest](#cart_add_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [CartAddRequest](#cart_add_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_create_request"></a>![Model: ](https://apidocs.io/img/method.png "CartCreateRequest") CartCreateRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Items | [Items](#items) |  ``` Required ```  | TODO: Add a property description | 
| MergeCart | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_create"></a>![Model: ](https://apidocs.io/img/method.png "CartCreate") CartCreate



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [CartCreateRequest](#cart_create_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [CartCreateRequest](#cart_create_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_modify_request"></a>![Model: ](https://apidocs.io/img/method.png "CartModifyRequest") CartModifyRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Items | [Items](#items) |  ``` Required ```  | TODO: Add a property description | 
| CartId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| HMAC | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MergeCart | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_modify"></a>![Model: ](https://apidocs.io/img/method.png "CartModify") CartModify



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [CartModifyRequest](#cart_modify_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [CartModifyRequest](#cart_modify_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_clear_request"></a>![Model: ](https://apidocs.io/img/method.png "CartClearRequest") CartClearRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| CartId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| HMAC | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MergeCart | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_clear"></a>![Model: ](https://apidocs.io/img/method.png "CartClear") CartClear



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [CartClearRequest](#cart_clear_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [CartClearRequest](#cart_clear_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="browse_node_lookup_request"></a>![Model: ](https://apidocs.io/img/method.png "BrowseNodeLookupRequest") BrowseNodeLookupRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| BrowseNodeId | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| ResponseGroup | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="browse_node_lookup"></a>![Model: ](https://apidocs.io/img/method.png "BrowseNodeLookup") BrowseNodeLookup



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| MarketplaceDomain | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AWSAccessKeyId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AssociateTag | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Validate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| XMLEscaping | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Shared | [BrowseNodeLookupRequest](#browse_node_lookup_request) |  ``` Optional ```  | TODO: Add a property description | 
| Request | [BrowseNodeLookupRequest](#browse_node_lookup_request) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="header"></a>![Model: ](https://apidocs.io/img/method.png "Header") Header



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Name | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Value | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="http_headers"></a>![Model: ](https://apidocs.io/img/method.png "HTTPHeaders") HTTPHeaders



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Header | [Header](#header) |  ``` Required ```  | TODO: Add a property description | 




### <a name="argument"></a>![Model: ](https://apidocs.io/img/method.png "Argument") Argument



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Name | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Value | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="arguments"></a>![Model: ](https://apidocs.io/img/method.png "Arguments") Arguments



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Argument | [Argument](#argument) |  ``` Required ```  | TODO: Add a property description | 




### <a name="error"></a>![Model: ](https://apidocs.io/img/method.png "Error") Error



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Code | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Message | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="errors"></a>![Model: ](https://apidocs.io/img/method.png "Errors") Errors



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Error | [Error](#error) |  ``` Required ```  | TODO: Add a property description | 




### <a name="operation_request"></a>![Model: ](https://apidocs.io/img/method.png "OperationRequest") OperationRequest



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| HTTPHeaders | [HTTPHeaders](#http_headers) |  ``` Optional ```  | TODO: Add a property description | 
| RequestId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Arguments | [Arguments](#arguments) |  ``` Optional ```  | TODO: Add a property description | 
| Errors | [Errors](#errors) |  ``` Optional ```  | TODO: Add a property description | 
| RequestProcessingTime | [precision](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="item_search_response"></a>![Model: ](https://apidocs.io/img/method.png "ItemSearchResponse") ItemSearchResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Items | [Items](#items) |  ``` Required ```  | TODO: Add a property description | 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="item_lookup_response"></a>![Model: ](https://apidocs.io/img/method.png "ItemLookupResponse") ItemLookupResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| Items | [Items](#items) |  ``` Required ```  | TODO: Add a property description | 




### <a name="similarity_lookup_response"></a>![Model: ](https://apidocs.io/img/method.png "SimilarityLookupResponse") SimilarityLookupResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| Items | [Items](#items) |  ``` Required ```  | TODO: Add a property description | 




### <a name="request"></a>![Model: ](https://apidocs.io/img/method.png "Request") Request



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| BrowseNodeLookupRequest | [BrowseNodeLookupRequest](#browse_node_lookup_request) |  ``` Required ```  | TODO: Add a property description | 
| ItemSearchRequest | [ItemSearchRequest](#item_search_request) |  ``` Required ```  | TODO: Add a property description | 
| ItemLookupRequest | [ItemLookupRequest](#item_lookup_request) |  ``` Required ```  | TODO: Add a property description | 
| SimilarityLookupRequest | [SimilarityLookupRequest](#similarity_lookup_request) |  ``` Required ```  | TODO: Add a property description | 
| CartGetRequest | [CartGetRequest](#cart_get_request) |  ``` Required ```  | TODO: Add a property description | 
| CartAddRequest | [CartAddRequest](#cart_add_request) |  ``` Required ```  | TODO: Add a property description | 
| CartCreateRequest | [CartCreateRequest](#cart_create_request) |  ``` Required ```  | TODO: Add a property description | 
| CartModifyRequest | [CartModifyRequest](#cart_modify_request) |  ``` Required ```  | TODO: Add a property description | 
| CartClearRequest | [CartClearRequest](#cart_clear_request) |  ``` Required ```  | TODO: Add a property description | 
| Errors | [Errors](#errors) |  ``` Required ```  | TODO: Add a property description | 
| IsValid | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="price"></a>![Model: ](https://apidocs.io/img/method.png "Price") Price



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| FormattedPrice | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Amount | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| CurrencyCode | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="key_value_pair"></a>![Model: ](https://apidocs.io/img/method.png "KeyValuePair") KeyValuePair



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Key | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Value | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="meta_data"></a>![Model: ](https://apidocs.io/img/method.png "MetaData") MetaData



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| KeyValuePair | [KeyValuePair](#key_value_pair) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_item"></a>![Model: ](https://apidocs.io/img/method.png "CartItem") CartItem



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| CartItemId | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Quantity | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| MetaData | [MetaData](#meta_data) |  ``` Required ```  | TODO: Add a property description | 
| Price | [Price](#price) |  ``` Required ```  | TODO: Add a property description | 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| SellerNickname | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ProductGroup | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ItemTotal | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="cart_items"></a>![Model: ](https://apidocs.io/img/method.png "CartItems") CartItems



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| CartItem | [CartItem](#cart_item) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 
| SubTotal | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="saved_for_later_items"></a>![Model: ](https://apidocs.io/img/method.png "SavedForLaterItems") SavedForLaterItems



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| SavedForLaterItem | [CartItem](#cart_item) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 
| SubTotal | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="similar_product"></a>![Model: ](https://apidocs.io/img/method.png "SimilarProduct") SimilarProduct



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="similar_products"></a>![Model: ](https://apidocs.io/img/method.png "SimilarProducts") SimilarProducts



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| SimilarProduct | [SimilarProduct](#similar_product) |  ``` Required ```  | TODO: Add a property description | 




### <a name="top_seller"></a>![Model: ](https://apidocs.io/img/method.png "TopSeller") TopSeller



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="top_sellers"></a>![Model: ](https://apidocs.io/img/method.png "TopSellers") TopSellers



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| TopSeller | [TopSeller](#top_seller) |  ``` Required ```  | TODO: Add a property description | 




### <a name="new_release"></a>![Model: ](https://apidocs.io/img/method.png "NewRelease") NewRelease



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="new_releases"></a>![Model: ](https://apidocs.io/img/method.png "NewReleases") NewReleases



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| NewRelease | [NewRelease](#new_release) |  ``` Required ```  | TODO: Add a property description | 




### <a name="similar_viewed_product"></a>![Model: ](https://apidocs.io/img/method.png "SimilarViewedProduct") SimilarViewedProduct



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="similar_viewed_products"></a>![Model: ](https://apidocs.io/img/method.png "SimilarViewedProducts") SimilarViewedProducts



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| SimilarViewedProduct | [SimilarViewedProduct](#similar_viewed_product) |  ``` Required ```  | TODO: Add a property description | 




### <a name="other_categories_similar_product"></a>![Model: ](https://apidocs.io/img/method.png "OtherCategoriesSimilarProduct") OtherCategoriesSimilarProduct



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="other_categories_similar_products"></a>![Model: ](https://apidocs.io/img/method.png "OtherCategoriesSimilarProducts") OtherCategoriesSimilarProducts



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OtherCategoriesSimilarProduct | [OtherCategoriesSimilarProduct](#other_categories_similar_product) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart"></a>![Model: ](https://apidocs.io/img/method.png "Cart") Cart



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| CartId | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| HMAC | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| URLEncodedHMAC | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Request | [Request](#request) |  ``` Optional ```  | TODO: Add a property description | 
| PurchaseURL | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MobileCartURL | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| SubTotal | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| CartItems | [CartItems](#cart_items) |  ``` Optional ```  | TODO: Add a property description | 
| SavedForLaterItems | [SavedForLaterItems](#saved_for_later_items) |  ``` Optional ```  | TODO: Add a property description | 
| SimilarProducts | [SimilarProducts](#similar_products) |  ``` Optional ```  | TODO: Add a property description | 
| TopSellers | [TopSellers](#top_sellers) |  ``` Optional ```  | TODO: Add a property description | 
| NewReleases | [NewReleases](#new_releases) |  ``` Optional ```  | TODO: Add a property description | 
| SimilarViewedProducts | [SimilarViewedProducts](#similar_viewed_products) |  ``` Optional ```  | TODO: Add a property description | 
| OtherCategoriesSimilarProducts | [OtherCategoriesSimilarProducts](#other_categories_similar_products) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="cart_get_response"></a>![Model: ](https://apidocs.io/img/method.png "CartGetResponse") CartGetResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| Cart | [Cart](#cart) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="cart_add_response"></a>![Model: ](https://apidocs.io/img/method.png "CartAddResponse") CartAddResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| Cart | [Cart](#cart) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_create_response"></a>![Model: ](https://apidocs.io/img/method.png "CartCreateResponse") CartCreateResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| Cart | [Cart](#cart) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_modify_response"></a>![Model: ](https://apidocs.io/img/method.png "CartModifyResponse") CartModifyResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| Cart | [Cart](#cart) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_clear_response"></a>![Model: ](https://apidocs.io/img/method.png "CartClearResponse") CartClearResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| Cart | [Cart](#cart) |  ``` Required ```  | TODO: Add a property description | 




### <a name="property"></a>![Model: ](https://apidocs.io/img/method.png "Property") Property



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Name | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Value | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="properties"></a>![Model: ](https://apidocs.io/img/method.png "Properties") Properties



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Property | [Property](#property) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="children"></a>![Model: ](https://apidocs.io/img/method.png "Children") Children



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| BrowseNode | [BrowseNode](#browse_node) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="ancestors"></a>![Model: ](https://apidocs.io/img/method.png "Ancestors") Ancestors



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| BrowseNode | [BrowseNode](#browse_node) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="top_item"></a>![Model: ](https://apidocs.io/img/method.png "TopItem") TopItem



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| DetailPageURL | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ProductGroup | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Author | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Artist | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Actor | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="top_item_set"></a>![Model: ](https://apidocs.io/img/method.png "TopItemSet") TopItemSet



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| TopItem | [TopItem](#top_item) |  ``` Required ```  | TODO: Add a property description | 
| Type | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="browse_node"></a>![Model: ](https://apidocs.io/img/method.png "BrowseNode") BrowseNode



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Properties | [Properties](#properties) |  ``` Required ```  | TODO: Add a property description | 
| Children | [Children](#children) |  ``` Required ```  | TODO: Add a property description | 
| Ancestors | [Ancestors](#ancestors) |  ``` Required ```  | TODO: Add a property description | 
| TopSellers | [TopSellers](#top_sellers) |  ``` Required ```  | TODO: Add a property description | 
| NewReleases | [NewReleases](#new_releases) |  ``` Required ```  | TODO: Add a property description | 
| BrowseNodeId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Name | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsCategoryRoot | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TopItemSet | [TopItemSet](#top_item_set) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="browse_nodes"></a>![Model: ](https://apidocs.io/img/method.png "BrowseNodes") BrowseNodes



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Request | [Request](#request) |  ``` Required ```  | TODO: Add a property description | 
| BrowseNode | [BrowseNode](#browse_node) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="browse_node_lookup_response"></a>![Model: ](https://apidocs.io/img/method.png "BrowseNodeLookupResponse") BrowseNodeLookupResponse



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| OperationRequest | [OperationRequest](#operation_request) |  ``` Required ```  | TODO: Add a property description | 
| BrowseNodes | [BrowseNodes](#browse_nodes) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="corrected_query"></a>![Model: ](https://apidocs.io/img/method.png "CorrectedQuery") CorrectedQuery



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Keywords | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Message | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="search_index"></a>![Model: ](https://apidocs.io/img/method.png "SearchIndex") SearchIndex



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| IndexName | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| CorrectedQuery | [CorrectedQuery](#corrected_query) |  ``` Required ```  | TODO: Add a property description | 
| RelevanceRank | [number](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| ASIN | [string](#api_types) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 
| Results | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Pages | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="search_results_map"></a>![Model: ](https://apidocs.io/img/method.png "SearchResultsMap") SearchResultsMap



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| SearchIndex | [SearchIndex](#search_index) |  ``` Required ```  | TODO: Add a property description | 




### <a name="merchant"></a>![Model: ](https://apidocs.io/img/method.png "Merchant") Merchant



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Name | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="non_negative_integer_with_units"></a>![Model: ](https://apidocs.io/img/method.png "NonNegativeIntegerWithUnits") NonNegativeIntegerWithUnits



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Units | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="rental_listing"></a>![Model: ](https://apidocs.io/img/method.png "RentalListing") RentalListing



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Price | [Price](#price) |  ``` Required ```  | TODO: Add a property description | 
| Period | [NonNegativeIntegerWithUnits](#non_negative_integer_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| IsFulfilledByAmazon | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Disclaimer | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="rental_offer"></a>![Model: ](https://apidocs.io/img/method.png "RentalOffer") RentalOffer



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Merchant | [Merchant](#merchant) |  ``` Optional ```  | TODO: Add a property description | 
| RentalListing | [RentalListing](#rental_listing) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="rental_offers"></a>![Model: ](https://apidocs.io/img/method.png "RentalOffers") RentalOffers



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| RentalOffer | [RentalOffer](#rental_offer) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="item_link"></a>![Model: ](https://apidocs.io/img/method.png "ItemLink") ItemLink



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Description | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| URL | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="item_links"></a>![Model: ](https://apidocs.io/img/method.png "ItemLinks") ItemLinks



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ItemLink | [ItemLink](#item_link) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="relationship"></a>![Model: ](https://apidocs.io/img/method.png "Relationship") Relationship



> TODO: Add a method description




This type must take a value from the following [string](#api_types) enumeration of values:

| Value | Description |
| ----- | --------------- |
| `Parents` | TODO: Add description | 
| `Children` | TODO: Add description | 




### <a name="related_item"></a>![Model: ](https://apidocs.io/img/method.png "RelatedItem") RelatedItem



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Item | [Item](#item) |  ``` Required ```  | TODO: Add a property description | 




### <a name="related_items"></a>![Model: ](https://apidocs.io/img/method.png "RelatedItems") RelatedItems



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Relationship | [Relationship](#relationship) |  ``` Required ```  | TODO: Add a property description | 
| RelationshipType | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelatedItemCount | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelatedItemPageCount | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelatedItemPage | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RelatedItem | [RelatedItem](#related_item) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="offer_summary"></a>![Model: ](https://apidocs.io/img/method.png "OfferSummary") OfferSummary



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| LowestNewPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| LowestUsedPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| LowestCollectiblePrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| LowestRefurbishedPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| TotalNew | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TotalUsed | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TotalCollectible | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TotalRefurbished | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="offer_attributes"></a>![Model: ](https://apidocs.io/img/method.png "OfferAttributes") OfferAttributes



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Condition | [Condition](#condition) |  ``` Required ```  | TODO: Add a property description | 




### <a name="availability_attributes"></a>![Model: ](https://apidocs.io/img/method.png "AvailabilityAttributes") AvailabilityAttributes



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| AvailabilityType | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsPreorder | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MinimumHours | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MaximumHours | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="offer_listing"></a>![Model: ](https://apidocs.io/img/method.png "OfferListing") OfferListing



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Price | [Price](#price) |  ``` Required ```  | TODO: Add a property description | 
| Availability | [Availability](#availability) |  ``` Required ```  | TODO: Add a property description | 
| AvailabilityAttributes | [AvailabilityAttributes](#availability_attributes) |  ``` Required ```  | TODO: Add a property description | 
| OfferListingId | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| PricePerUnit | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| SalePrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| AmountSaved | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| PercentageSaved | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsEligibleForSuperSaverShipping | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsEligibleForPrimeFreeDigitalVideo | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsEligibleForPrime | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="loyalty_points"></a>![Model: ](https://apidocs.io/img/method.png "LoyaltyPoints") LoyaltyPoints



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Points | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TypicalRedemptionValue | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="summary"></a>![Model: ](https://apidocs.io/img/method.png "Summary") Summary



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| PromotionId | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Message | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Category | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| StartDate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| EndDate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| EligibilityRequirementDescription | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| BenefitDescription | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TermsAndConditions | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="promotion"></a>![Model: ](https://apidocs.io/img/method.png "Promotion") Promotion



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Summary | [Summary](#summary) |  ``` Required ```  | TODO: Add a property description | 




### <a name="promotions"></a>![Model: ](https://apidocs.io/img/method.png "Promotions") Promotions



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Promotion | [Promotion](#promotion) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="offer"></a>![Model: ](https://apidocs.io/img/method.png "Offer") Offer



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Merchant | [Merchant](#merchant) |  ``` Required ```  | TODO: Add a property description | 
| OfferAttributes | [OfferAttributes](#offer_attributes) |  ``` Optional ```  | TODO: Add a property description | 
| OfferListing | [OfferListing](#offer_listing) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| LoyaltyPoints | [LoyaltyPoints](#loyalty_points) |  ``` Optional ```  | TODO: Add a property description | 
| Promotions | [Promotions](#promotions) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="offers"></a>![Model: ](https://apidocs.io/img/method.png "Offers") Offers



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| TotalOffers | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TotalOfferPages | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MoreOffersUrl | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Offer | [Offer](#offer) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="variation_attribute"></a>![Model: ](https://apidocs.io/img/method.png "VariationAttribute") VariationAttribute



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Name | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Value | [string](#api_types) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="variation_summary"></a>![Model: ](https://apidocs.io/img/method.png "VariationSummary") VariationSummary



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| LowestPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| HighestPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| LowestSalePrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| HighestSalePrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="variation_dimensions"></a>![Model: ](https://apidocs.io/img/method.png "VariationDimensions") VariationDimensions



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| VariationDimension | [string](#api_types) |  ``` Required ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="variations"></a>![Model: ](https://apidocs.io/img/method.png "Variations") Variations



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Item | [Item](#item) |  ``` Required ```  | TODO: Add a property description | 
| TotalVariations | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TotalVariationPages | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| VariationDimensions | [VariationDimensions](#variation_dimensions) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="editorial_review"></a>![Model: ](https://apidocs.io/img/method.png "EditorialReview") EditorialReview



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Source | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Content | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsLinkSuppressed | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="editorial_reviews"></a>![Model: ](https://apidocs.io/img/method.png "EditorialReviews") EditorialReviews



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| EditorialReview | [EditorialReview](#editorial_review) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="collection_summary"></a>![Model: ](https://apidocs.io/img/method.png "CollectionSummary") CollectionSummary



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| LowestListPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| HighestListPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| LowestSalePrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| HighestSalePrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="collection_parent"></a>![Model: ](https://apidocs.io/img/method.png "CollectionParent") CollectionParent



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="collection_item"></a>![Model: ](https://apidocs.io/img/method.png "CollectionItem") CollectionItem



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="collection"></a>![Model: ](https://apidocs.io/img/method.png "Collection") Collection



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| CollectionSummary | [CollectionSummary](#collection_summary) |  ``` Required ```  | TODO: Add a property description | 
| CollectionParent | [CollectionParent](#collection_parent) |  ``` Required ```  | TODO: Add a property description | 
| CollectionItem | [CollectionItem](#collection_item) |  ``` Required ```  | TODO: Add a property description | 




### <a name="collections"></a>![Model: ](https://apidocs.io/img/method.png "Collections") Collections



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Collection | [Collection](#collection) |  ``` Required ```  | TODO: Add a property description | 




### <a name="customer_reviews"></a>![Model: ](https://apidocs.io/img/method.png "CustomerReviews") CustomerReviews



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| IFrameURL | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| HasReviews | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="track"></a>![Model: ](https://apidocs.io/img/method.png "Track") Track



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Number | [number](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="disc"></a>![Model: ](https://apidocs.io/img/method.png "Disc") Disc



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Number | [number](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Track | [Track](#track) |  ``` Required ```  | TODO: Add a property description | 




### <a name="tracks"></a>![Model: ](https://apidocs.io/img/method.png "Tracks") Tracks



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Disc | [Disc](#disc) |  ``` Required ```  | TODO: Add a property description | 




### <a name="accessory"></a>![Model: ](https://apidocs.io/img/method.png "Accessory") Accessory



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| ASIN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="accessories"></a>![Model: ](https://apidocs.io/img/method.png "Accessories") Accessories



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Accessory | [Accessory](#accessory) |  ``` Required ```  | TODO: Add a property description | 




### <a name="decimal_with_units"></a>![Model: ](https://apidocs.io/img/method.png "DecimalWithUnits") DecimalWithUnits



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Units | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="image"></a>![Model: ](https://apidocs.io/img/method.png "Image") Image



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| URL | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Height | [DecimalWithUnits](#decimal_with_units) |  ``` Required ```  | TODO: Add a property description | 
| Width | [DecimalWithUnits](#decimal_with_units) |  ``` Required ```  | TODO: Add a property description | 
| IsVerified | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="image_set"></a>![Model: ](https://apidocs.io/img/method.png "ImageSet") ImageSet



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Category | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| SwatchImage | [Image](#image) |  ``` Optional ```  | TODO: Add a property description | 
| SmallImage | [Image](#image) |  ``` Optional ```  | TODO: Add a property description | 
| ThumbnailImage | [Image](#image) |  ``` Optional ```  | TODO: Add a property description | 
| TinyImage | [Image](#image) |  ``` Optional ```  | TODO: Add a property description | 
| MediumImage | [Image](#image) |  ``` Optional ```  | TODO: Add a property description | 
| LargeImage | [Image](#image) |  ``` Optional ```  | TODO: Add a property description | 
| HiResImage | [Image](#image) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="catalog_number_list"></a>![Model: ](https://apidocs.io/img/method.png "CatalogNumberList") CatalogNumberList



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| CatalogNumberListElement | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="creator"></a>![Model: ](https://apidocs.io/img/method.png "Creator") Creator



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Role | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="ean_list"></a>![Model: ](https://apidocs.io/img/method.png "EANList") EANList



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| EANListElement | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="item_dimensions"></a>![Model: ](https://apidocs.io/img/method.png "ItemDimensions") ItemDimensions



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Height | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| Length | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| Weight | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| Width | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="language"></a>![Model: ](https://apidocs.io/img/method.png "Language") Language



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Name | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 
| Type | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AudioFormat | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="languages"></a>![Model: ](https://apidocs.io/img/method.png "Languages") Languages



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Language | [Language](#language) |  ``` Required ```  | TODO: Add a property description | 




### <a name="package_dimensions"></a>![Model: ](https://apidocs.io/img/method.png "PackageDimensions") PackageDimensions



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Height | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| Length | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| Weight | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| Width | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="upc_list"></a>![Model: ](https://apidocs.io/img/method.png "UPCList") UPCList



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| UPCListElement | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 




### <a name="item_attributes"></a>![Model: ](https://apidocs.io/img/method.png "ItemAttributes") ItemAttributes



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| AudienceRating | [AudienceRating](#audience_rating) |  ``` Required ```  | TODO: Add a property description | 
| CatalogNumberList | [CatalogNumberList](#catalog_number_list) |  ``` Required ```  | TODO: Add a property description | 
| Creator | [Creator](#creator) |  ``` Required ```  | TODO: Add a property description | 
| EANList | [EANList](#ean_list) |  ``` Required ```  | TODO: Add a property description | 
| ItemDimensions | [ItemDimensions](#item_dimensions) |  ``` Required ```  | TODO: Add a property description | 
| Languages | [Languages](#languages) |  ``` Required ```  | TODO: Add a property description | 
| PackageDimensions | [PackageDimensions](#package_dimensions) |  ``` Required ```  | TODO: Add a property description | 
| UPCList | [UPCList](#upc_list) |  ``` Required ```  | TODO: Add a property description | 
| Actor | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Artist | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| AspectRatio | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| AudioFormat | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Author | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Binding | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Brand | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Category | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| CEROAgeRating | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ClothingSize | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Color | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Department | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Director | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| EAN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Edition | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| EISBN | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| EnergyEfficiencyClass | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| EpisodeSequence | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ESRBAgeRating | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Feature | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Format | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Genre | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| HardwarePlatform | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| HazardousMaterialType | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsAdultProduct | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsAutographed | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ISBN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsEligibleForTradeIn | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IsMemorabilia | [boolean](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| IssuesPerYear | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ItemPartNumber | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Label | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| LegalDisclaimer | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ListPrice | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| MagazineType | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Manufacturer | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ManufacturerMaximumAge | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| ManufacturerMinimumAge | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| ManufacturerPartsWarrantyDescription | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MediaType | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Model | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ModelYear | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| MPN | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| NumberOfDiscs | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| NumberOfIssues | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| NumberOfItems | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| NumberOfPages | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| NumberOfTracks | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| OperatingSystem | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| PackageQuantity | [number](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| PartNumber | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| PictureFormat | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| Platform | [string](#api_types) |  ``` Optional ```  ``` Collection ```  | TODO: Add a property description | 
| ProductGroup | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ProductTypeName | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ProductTypeSubcategory | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| PublicationDate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Publisher | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RegionCode | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| ReleaseDate | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| SeasonSequence | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| RunningTime | [DecimalWithUnits](#decimal_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| SeikodoProductCode | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Size | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| SKU | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Studio | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| SubscriptionLength | [NonNegativeIntegerWithUnits](#non_negative_integer_with_units) |  ``` Optional ```  | TODO: Add a property description | 
| Title | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TrackSequence | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| TradeInValue | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 
| UPC | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| Warranty | [string](#api_types) |  ``` Optional ```  | TODO: Add a property description | 
| WEEETaxValue | [Price](#price) |  ``` Optional ```  | TODO: Add a property description | 




### <a name="string_with_units"></a>![Model: ](https://apidocs.io/img/method.png "StringWithUnits") StringWithUnits



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| Units | [string](#api_types) |  ``` Required ```  | TODO: Add a property description | 




### <a name="item_search_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "ItemSearchResponseMsg") ItemSearchResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [ItemSearchResponse](#item_search_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="item_lookup_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "ItemLookupResponseMsg") ItemLookupResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [ItemLookupResponse](#item_lookup_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="browse_node_lookup_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "BrowseNodeLookupResponseMsg") BrowseNodeLookupResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [BrowseNodeLookupResponse](#browse_node_lookup_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="similarity_lookup_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "SimilarityLookupResponseMsg") SimilarityLookupResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [SimilarityLookupResponse](#similarity_lookup_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_get_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartGetResponseMsg") CartGetResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartGetResponse](#cart_get_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_add_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartAddResponseMsg") CartAddResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartAddResponse](#cart_add_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_create_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartCreateResponseMsg") CartCreateResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartCreateResponse](#cart_create_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_modify_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartModifyResponseMsg") CartModifyResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartModifyResponse](#cart_modify_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_clear_response_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartClearResponseMsg") CartClearResponseMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartClearResponse](#cart_clear_response) |  ``` Required ```  | TODO: Add a property description | 




### <a name="item_search_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "ItemSearchRequestMsg") ItemSearchRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [ItemSearch](#item_search) |  ``` Required ```  | TODO: Add a property description | 




### <a name="item_lookup_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "ItemLookupRequestMsg") ItemLookupRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [ItemLookup](#item_lookup) |  ``` Required ```  | TODO: Add a property description | 




### <a name="browse_node_lookup_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "BrowseNodeLookupRequestMsg") BrowseNodeLookupRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [BrowseNodeLookup](#browse_node_lookup) |  ``` Required ```  | TODO: Add a property description | 




### <a name="similarity_lookup_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "SimilarityLookupRequestMsg") SimilarityLookupRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [SimilarityLookup](#similarity_lookup) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_get_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartGetRequestMsg") CartGetRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartGet](#cart_get) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_add_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartAddRequestMsg") CartAddRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartAdd](#cart_add) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_create_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartCreateRequestMsg") CartCreateRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartCreate](#cart_create) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_modify_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartModifyRequestMsg") CartModifyRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartModify](#cart_modify) |  ``` Required ```  | TODO: Add a property description | 




### <a name="cart_clear_request_msg"></a>![Model: ](https://apidocs.io/img/method.png "CartClearRequestMsg") CartClearRequestMsg



> TODO: Add a method description




| Name | Type | Tags | Description |
|-----------|------| ---- |-------------| 
| body | [CartClear](#cart_clear) |  ``` Required ```  | TODO: Add a property description |

