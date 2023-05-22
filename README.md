# metatransaction_python
approve를 이용한 메타트랜잭션
사용법: \n
meta_fowarder.sol 배포 -> erc 20 컨트랙트에서 metatran을 이용할 사람이 meta_fowarder contract address에 approve(approve 수량이 많으면 계속 메타트랜잭션을 사용가능함)
-> erc 20 컨트랙트 주소를 add whitelist를 사용해서 등록 (meta_fowarder owner가 등록해줘야함) -> make_signature을 이용해 사인 생성후 meta_transfer 실행 \n
결론적으로 metatran 을 이용할 이용자는 approve 수수료 비용만 사용하면 approve한 수량에 맞게 계속 대납 트랜잭션이 사용 가능하다.

