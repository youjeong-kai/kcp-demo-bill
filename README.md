# kcp-demo-bill

시연용 신용카드 매출전표 정적 페이지. 서버 없이 쿼리 파라미터로 전표를 그립니다.

`bill/card/?cmd=card_bill&tno=<거래번호>&order_no=<주문번호>&trade_mony=<금액>&mall=<가맹점명>&card=<카드사>&card_no=<마스킹 카드번호>&appr=<승인번호>&paid_at=<결제일시>`

취소 전표: `cmd=card_cancel_bill&status=cancel&cancel_at=<취소일시>&cancel_type=partial`
