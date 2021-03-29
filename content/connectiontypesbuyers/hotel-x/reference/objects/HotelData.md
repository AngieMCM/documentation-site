{
  "title": "HotelData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "code",
      "url": "/hotel-x/reference/scalars/id",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "hotelCode",
      "url": "/hotel-x/reference/scalars/string",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "hotelCodeSupplier",
      "url": "/hotel-x/reference/scalars/string",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "GiataData",
      "name": "giataData",
      "url": "/hotel-x/reference/objects/giatadata",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "hotelName",
      "url": "/hotel-x/reference/scalars/string",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "categoryCode",
      "url": "/hotel-x/reference/scalars/string",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Property",
      "name": "property",
      "url": "/hotel-x/reference/objects/property",
      "description": null,
      "isDeprecated": true,
      "args": null,
      "deprecationReason": "Deprecated from 2019-10-16. Redundant information",
      "descriptionSplitted": {
        "date": "2019-10-16",
        "first": "Deprecated from",
        "second": "Redundant information"
      },
      "deprecationDate": "2019-10-16",
      "typeName": "HotelData"
    },
    {
      "typeString": "String",
      "name": "chainCode",
      "url": "/hotel-x/reference/scalars/string",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "exclusiveDeal",
      "url": "/hotel-x/reference/scalars/boolean",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Location!",
      "name": "location",
      "url": "/hotel-x/reference/objects/location",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Contact",
      "name": "contact",
      "url": "/hotel-x/reference/objects/contact",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Int!]!",
      "name": "rank",
      "url": "/hotel-x/reference/scalars/int",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[PaymentCardType!]",
      "name": "cardTypes",
      "url": "/hotel-x/reference/enums/paymentcardtype",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[AmenityStatic!]",
      "name": "amenities",
      "url": "/hotel-x/reference/objects/amenitystatic",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Media!]",
      "name": "medias",
      "url": "/hotel-x/reference/objects/media",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[Description!]",
      "name": "descriptions",
      "url": "/hotel-x/reference/objects/description",
      "description": null,
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[DescriptionType!]",
          "name": "types",
          "url": "/hotel-x/reference/enums/descriptiontype",
          "description": null
        },
        {
          "typeString": "[Language!]",
          "name": "languages",
          "url": "/hotel-x/reference/scalars/language",
          "description": null
        }
      ]
    },
    {
      "typeString": "RoomConnection",
      "name": "rooms",
      "url": "/hotel-x/reference/objects/roomconnection",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "PropertyType",
      "name": "propertyType",
      "url": "/hotel-x/reference/objects/propertytype",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "[MandatoryFee!]",
      "name": "mandatoryFees",
      "url": "/hotel-x/reference/objects/mandatoryfee",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "CheckInformation",
      "name": "checkIn",
      "url": "/hotel-x/reference/objects/checkinformation",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "CheckInformation",
      "name": "checkOut",
      "url": "/hotel-x/reference/objects/checkinformation",
      "description": null,
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "HotelXAmenityConnection",
      "name": "allAmenities",
      "url": "/hotel-x/reference/objects/hotelxamenityconnection",
      "description": null,
      "isDeprecated": false,
      "args": [
        {
          "typeString": "[HotelXMapOptionInput!]",
          "name": "mapOptions",
          "url": "/hotel-x/reference/inputobjects/hotelxmapoptioninput",
          "description": null
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Hotel",
      "description": null,
      "url": "/hotel-x/reference/objects/hotel"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "HotelData",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
