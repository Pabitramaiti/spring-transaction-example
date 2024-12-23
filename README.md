# spring-transaction-example
<br>
Endpoint(POST): http://localhost:8080/booking/bookFlightTicket

FAILURE
----------
{
    "passengerInfo" :{
        "name": "Pabitra",
        "email": "pabitramail03@gmail.com",
        "source": "Bangalore",
        "Destination": "Kolkata",
        "travelDate": "24-12-2024",
        "pickupTime": "4.0 PM",
        "arrivalTime": "6.0 PM",
        "fare": 15000.0
    },
    "paymentInfo" :{
        "accountNo": "acc1",
        "cardType": "DEBIT"
    }
}

SUCCESS
----------
{
    "passengerInfo" :{
        "name": "Pabitra",
        "email": "pabitramail03@gmail.com",
        "source": "Bangalore",
        "Destination": "Kolkata",
        "travelDate": "24-12-2024",
        "pickupTime": "4.0 PM",
        "arrivalTime": "6.0 PM",
        "fare": 10000.0
    },
    "paymentInfo" :{
        "accountNo": "acc2",
        "cardType": "DEBIT"
    }
}