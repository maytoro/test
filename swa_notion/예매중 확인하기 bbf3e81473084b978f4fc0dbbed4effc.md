# 예매중 확인하기

HTTP 메서드: GET
API URL: /api/neticket/ticket-info/{ticketInfoId}

(@Pathvariable)
Response: {
"image": "randomUUID_xx콘서트.jpg",
”eventId”: 12345,
”title”: “공연제목”,
”place”: “공연장소”,
”price”: “ 가격(1장당가격)”,
”date”: “공연날짜”,
”ticketInfoDto”: 
[
”ticketInfoid”: 1,
”openDate”: “티켓오픈시간,
”leftSeate”: “남은 좌석 수”
]
}
비고: ReservationController