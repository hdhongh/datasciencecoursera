# fabric
Hypereldger Fabric Daliy Log ( 2018/05/08 )

- Fabric Client SDK 활용
  1. Fabric Client Instance 새성
  2. Fabric Client 타임아웃 설정
  3. Fabric Client newChannel 생성 ( input : channelName )
  4. Fabric Client newOrderer 생성 ( input : url, pem data )
  5. Fabric Client newPeer 생성 ( input : request url, pem data )
  6. Set Client Configuration :
    - HFC.newDeFualtKeyValueStore(path)
    - HFC.newCryptoKeyStore(path)
  7. Set Client Context (input : name, fabricClient )
    - member.getMember(client, name)
  8. connect Event peers (input : event Peers )
