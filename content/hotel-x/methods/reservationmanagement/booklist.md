{
"title": "Booking List",
"pagetitle": "Booking List",
"description": "How to request for booking detail",
"icon": "fa-list",
"weight": 1,
"alwaysopen": false,
"default_ak": "64780338-49c8-4439-7c7d-d03c2033b145",
"default_user": "",
"gists": [
    {
        "n":"By Dates",
        "g":"2bee5af21dd6f2cc61eec736bb95aead",
        "o":["graphiql"],
        "u":"tgx-bot",
        "ak":"64780338-49c8-4439-7c7d-d03c2033b145"
    }, 
    {
        "n":"By Reference",
        "g":"a5b25332a7a5683d602efeb87233a9c7",
        "o":["graphiql"],
        "u":"tgx-bot",
        "ak":"64780338-49c8-4439-7c7d-d03c2033b145"
    },
    {
        "n":"By BookingID",
        "g":"133143d655be0783914dff46b66c96f4",
        "o":["graphiql"],
        "u":"tgx-bot",
        "ak":"64780338-49c8-4439-7c7d-d03c2033b145"
    }
        ]
}

The Booking operation allows to retrieve a booking (or bookings) with all its details from the booking reference locator.
The most important information returned for each booking in the list is:
* Booking reference
* Booking holder
* Booking pax
* Hotel, rooms and boards confirmed
* Booking rates

## Advanced criteria
There are three different types of booking search:
* By reference
* By dates
* By bookingID

## How to request
{{% graphiql-tabs %}}

a5b25332a7a5683d602efeb87233a9c7
You can ask for bookings by client reference (XTG-XXXXXX) or by supplier reference.
/a5b25332a7a5683d602efeb87233a9c7

{{% /graphiql-tabs %}}

{{< graphiql-styles >}}
{{% graphiql-script-tabs %}}

## Bear in mind
{{% alert theme="warning" %}}
_Remember that you can choose which information you want to show_

**Reference:** To show client or supplier booking reference

**Status:** To show the booking status

If you want to ask for one booking, you can send the client/supplier booking reference on the HotelCriteriaBooking
{{% /alert %}}