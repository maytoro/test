# Redis 좌석 수 저장

HTTP 메서드: POST
API URL: /api/neticket/cache/left-seats/{ticketInfoId}

(@Pathvariable)
Request Header: header
Authorization: 토큰정보
Response: {
    "msg": "redis에 성공적으로 저장되었습니다.",
    "statusCode": 201
}
비고: AdminController