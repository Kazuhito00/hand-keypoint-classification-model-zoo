# hand-keypoint-classification-model-zoo
[Kazuhito00/hand-gesture-recognition-using-mediapipe](https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe) のキーポイント分類を寄せ集めたリポジトリです。

# Requirements
* mediapipe 0.8.4
* OpenCV 4.6.0.66 or Later
* Tensorflow 2.9.0 or Later
* protobuf <3.20,>=3.9.2

# Demo
Webカメラを使ったデモの実行方法は以下です。
```bash
python main.py
```

デモ実行時には、以下のオプションが指定可能です。
* --model<br>デモで使用するモデルの作者指定 (デフォルト：Kazuhito00)
* --device<br>カメラデバイス番号の指定 (デフォルト：0)
* --width<br>カメラキャプチャ時の横幅 (デフォルト：960)
* --height<br>カメラキャプチャ時の縦幅 (デフォルト：540)
* --use_static_image_mode<br>MediaPipeの推論にstatic_image_modeを利用するか否か (デフォルト：未指定)
* --min_detection_confidence<br>
検出信頼値の閾値 (デフォルト：0.5)
* --min_tracking_confidence<br>
トラッキング信頼値の閾値 (デフォルト：0.5)
* --unuse_brect<br>矩形を描画しないようにする (デフォルト：未指定)

# Model Zoo
## オリジナルリポジトリ<br>[Kazuhito00/hand-gesture-recognition-using-mediapipe](https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe)
Model Name:Kazuhito00
<br><img src="https://user-images.githubusercontent.com/37477845/229668680-31630dcc-e40f-4899-a7c4-0ae6f1111a28.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229668728-0362bbeb-ced8-47c5-a5ca-a7d7a194a27c.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229668753-27e2dd6c-611c-4b09-9845-a29b97bfb223.png" loading="lazy" width="250px">

## [AladdinT/hand-gesture-remote-controller](https://github.com/AladdinT/hand-gesture-remote-controller)
Model Name:AladdinT
<br><img src="https://user-images.githubusercontent.com/37477845/229669334-4fba5e60-d941-45ad-b309-0122891198f7.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229669553-48141da9-6e25-4dd7-97f3-2fe19fd00f66.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229669618-7eae98a7-a2b2-46ae-970c-2dc23dd4b2a9.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229669682-d519e3c8-e720-4013-bd93-e9e43b1310e4.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229669901-96d54b53-9d5e-4f14-ad71-bef072f95141.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229669921-4a902b64-7cb9-4721-b242-da6ccbb75551.png" loading="lazy" width="250px">

## [avazahedi/go1-gesture-command](https://github.com/avazahedi/go1-gesture-command)
Model Name:avazahedi
<br><img src="https://user-images.githubusercontent.com/37477845/229668680-31630dcc-e40f-4899-a7c4-0ae6f1111a28.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229668728-0362bbeb-ced8-47c5-a5ca-a7d7a194a27c.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229668753-27e2dd6c-611c-4b09-9845-a29b97bfb223.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229670591-73cb349e-9516-4a15-9686-27318a090c59.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229670616-aff0298f-fe7e-4812-8141-8c010d8ce4da.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229670644-7897742b-1362-4dae-a291-2ae4a17a95ed.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229670726-1e345416-5025-4c87-813a-461cd2168598.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229670807-fa5c7d06-3851-4863-8815-78284b7ce9b4.png" loading="lazy" width="250px">

<!-- まだモデルがコミットされていない
## [jquintanilla4/hand-gesture-recognition](https://github.com/jquintanilla4/hand-gesture-recognition)
Model Name:jquintanilla4
<br><img src="" loading="lazy" width="250px">　<img src="" loading="lazy" width="250px">　<img src="" loading="lazy" width="250px">
-->

## [vincentvilo/hand-gesture-control](https://github.com/vincentvilo/hand-gesture-control)
Model Name:vincentvilo
<br><img src="https://user-images.githubusercontent.com/37477845/229671891-d25f08ab-4c2f-45a7-9d3c-b1e6aa023474.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229671979-72de648e-77dd-4b75-941a-2202c314e94d.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229672056-21379bed-f216-46be-8d49-df397541ccbd.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229672156-4ee6d757-9e4e-49fe-8a91-601b5c7236b8.png" loading="lazy" width="250px">

<!-- モデル改造されているため、そのまま動かない
## [Jsgrooss/Fingerspelling-Thesis](https://github.com/Jsgrooss/Fingerspelling-Thesis)
Model Name:jquintanilla4
<br><img src="" loading="lazy" width="250px">　<img src="" loading="lazy" width="250px">　<img src="" loading="lazy" width="250px">
-->

## [fredericomcorda/hand-gesture-recognition-mediapipe](https://github.com/fredericomcorda/hand-gesture-recognition-mediapipe)
Model Name:fredericomcorda
<br><img src="https://user-images.githubusercontent.com/37477845/229674599-cfbd8eaa-5eef-4470-937e-c84a443b7cd9.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229674667-1882df22-32fe-4cb5-96b4-2d70b6084b8f.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229674878-6a82300f-7844-47d2-9adb-293927edab54.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229674908-127c1bf9-5d8f-4035-be6c-7bcb6d9b9ba1.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229674941-f227fcd2-c46d-47c7-976d-c22816194307.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229674966-54000373-895c-4f45-aca2-1ed02095701a.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229675000-729caf87-7f41-45be-9605-7e1c84fc29b6.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229675025-d18761c5-6113-4ed4-843c-b3000c8bd3a1.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229675076-ccd36cb0-e92e-4863-9dc5-227c38f60204.png" loading="lazy" width="250px">

## [GhoshRitika/go1-gesture-command](https://github.com/GhoshRitika/go1-gesture-command)
Model Name:GhoshRitika
<br><img src="https://user-images.githubusercontent.com/37477845/229685148-7e088597-2e4e-4e3e-9b7d-f2f065321bd7.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229685157-6791a55f-b90d-4863-9c7a-6291ec4dae1d.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229685193-ea26bc02-ddf7-4549-b0cc-bf64a6b07150.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229685222-9f1dfe14-31de-4aa1-88dd-cbaa0e18197d.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229685280-cadc08cd-0a24-43e7-8f06-62f806752281.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229685322-a03b4662-b0c8-4234-91a3-8739f4e71a3a.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229685343-e1c91d7b-c76a-40f0-976c-e24ead097b41.png" loading="lazy" width="250px">

## [thomasbridgemanatu/hand-gesture-recognition-mediapipe](https://github.com/thomasbridgemanatu/hand-gesture-recognition-mediapipe)
Model Name:thomasbridgemanatu
<br><img src="https://user-images.githubusercontent.com/37477845/229685903-39fbe2d2-18dc-41fd-aefe-530e23c31631.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229685930-ba816ca1-b56e-40f7-a355-b7f7bb5bee5d.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229685945-33c7f5c9-80e5-4e93-9186-41647991584f.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229685962-22a8ae74-f205-4504-b8db-c1f8f9a475ba.png" loading="lazy" width="250px">

<!-- Twoが動かない
## [Bryce138675/hand-gesture-recognition-mediapipe](https://github.com/Bryce138675/hand-gesture-recognition-mediapipe)
Model Name:Bryce138675
<br><img src="https://user-images.githubusercontent.com/37477845/229686323-e4e80643-2418-48b7-ba05-0c467a8e9617.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229686338-790414c3-2d8f-425b-969f-d53604507b3b.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229686365-be543049-f598-4089-8743-07b7f4dee8ef.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229686383-306c380b-2d30-4498-90e4-5fa589c20079.png" loading="lazy" width="250px">
-->

## [kinivi/hand-gesture-recognition-mediapipe](https://github.com/kinivi/hand-gesture-recognition-mediapipe)
Model Name:kinivi
<br><img src="https://user-images.githubusercontent.com/37477845/229687190-b45ed3a4-527b-4a45-8d0f-7aea1a1d72a9.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229687233-6a6219ee-e2aa-4d3c-8534-5442e6702b7f.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229687263-98991037-d4cf-49a3-9f3c-14bb1095b4cd.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229687306-12a6e4f7-7fd6-4cea-b028-aa491a587a00.png" loading="lazy" width="250px">

## [NongPO/hand-gesture-recognition-mediapipe](https://github.com/NongPO/hand-gesture-recognition-mediapipe)
Model Name:NongPO
<br><img src="https://user-images.githubusercontent.com/37477845/229687727-24d0c0f6-d569-4574-bb6b-f2d5e24a6bf9.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229687749-a7d66877-18a4-4df9-9a06-536c4aad269d.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229687827-ed1c8b87-53db-4778-a8ad-506ed8f33e24.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229687881-cd0837ee-5dec-4be3-bd88-6a6cc0942a1f.png" loading="lazy" width="250px">

## [mariuccatalin/hand-gesture-recognition-mediapipe](https://github.com/mariuccatalin/hand-gesture-recognition-mediapipe)
Model Name:mariuccatalin
<br><img src="https://user-images.githubusercontent.com/37477845/229688331-c14dfb2a-e27b-499a-940f-c2f788b11fe0.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229688341-21f8fb63-a3e9-4e5d-99f2-d13647984f67.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229688353-f8ee1f68-f48c-47e1-882b-ad89afe736bf.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229688398-3b0f8d30-ffb8-4898-8b20-fcffb165b55b.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229688422-7b362f49-acd2-4735-a62f-1ff8c7d7bca6.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229688656-44c517de-b127-4cb0-921f-bc42776ac13e.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229688474-354d97c9-a6af-43e5-bd4e-7340d0a12262.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229688505-d8bc164d-5a61-45c1-94e2-6e9bc144a401.png" loading="lazy" width="250px">　<img src="https://user-images.githubusercontent.com/37477845/229688562-bed6cc32-0dd0-4598-ada2-c2d0fcfb04da.png" loading="lazy" width="250px">

## [sandesh8888/hand-gesture-recognition-mediapipe](https://github.com/sandesh8888/hand-gesture-recognition-mediapipe)
Model Name:sandesh8888
<br><img src="https://user-images.githubusercontent.com/37477845/229691228-5057e208-8cac-41c7-b84a-6b2d263a71a3.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229691272-87b4d7ee-606a-40f1-86bd-5c378814af9b.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229691303-aa1a89e2-750c-4533-ab1d-b9eaa4665067.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229691323-039c1938-0acb-41a1-95bc-714ae8fe2315.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229691367-cef11dd5-6038-42fd-a12a-892a38adce73.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229691397-8d5d950c-b43c-430f-8d0e-522901909259.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229691429-da8f3d38-84f4-42f1-9b24-f547690f619f.png" loading="lazy" width="250px">

## [LepronlineR/hand-gesture-recognition-mediapipe](https://github.com/LepronlineR/hand-gesture-recognition-mediapipe)
Model Name:LepronlineR
<br><img src="https://user-images.githubusercontent.com/37477845/229692833-5df3c7af-431e-46fe-89db-d4a72423892a.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229692848-e9bcf289-8155-42d8-b46c-2c1b5eae0141.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229692876-dd41c32e-3fb0-4b60-9108-5f639e6d64bd.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229692901-bc310f2d-a231-4488-bd2a-f6c6c4b657ee.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229692946-578d2bd7-9ca8-481f-a2ed-29ff0c1421f1.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229692974-35db22e2-2e37-4ed8-ab59-6f17bb861128.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229693015-af857a3e-5887-4336-a81d-9ba9026f3efa.png" loading="lazy" width="250px">　

## [thinkall/hand-gesture-recognition-mediapipe](https://github.com/thinkall/hand-gesture-recognition-mediapipe)
Model Name:thinkall
<br><img src="https://user-images.githubusercontent.com/37477845/229693882-3c6203de-aa6c-472b-91b8-c0cd6d22a6fa.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229693901-77ca4dff-e198-4dfc-bae0-1049144c8eee.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229693930-bfad06fd-1263-4ead-ad59-9d2c38ab2e07.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229693949-78f9103f-2cf0-4b1a-8ebd-cc324cbf2109.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229694014-f34c243d-f4ed-47db-b355-d5484d2c3184.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229694037-1d0ce968-cbc5-48ce-9e71-1e896f843846.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229694080-c0949c70-95ed-4bec-ab89-8fe2a8c95b29.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229694102-5135ad76-c4d8-4a90-9314-6914a1934218.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229694181-ac8b6bbc-a984-4dab-b4e1-9735400434fa.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229694959-e126c11a-6fcc-4dd2-b860-6540eb5a6920.png" loading="lazy" width="250px">　

## [kch3coo/hand-gesture-recognition-mediapipe](https://github.com/kch3coo/hand-gesture-recognition-mediapipe)
Model Name:kch3coo
<br><img src="https://user-images.githubusercontent.com/37477845/229759958-d5258a26-0e3c-49fe-85aa-756a63ca2809.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229760106-4afbf744-7876-466b-860f-535f8eea35a2.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229760203-24f30a72-0415-4d7b-aef4-3ea9f60bfb63.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229760468-8f935d75-7ce2-464b-98a8-8ab827d2902c.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229760669-42ed7ac9-0be8-45ee-bf47-de5393f45266.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229760801-464011cd-b948-4b94-b316-53d0242b9866.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229760884-62b29ef2-38ce-4d4a-b25c-4de9cf288bca.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229760957-98fc2886-9f65-4a31-9075-2dd170342474.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229761077-dc51b31b-9cdb-4de3-8321-d03ffeac0fab.png" loading="lazy" width="250px">

## [jaeeun/hand-gesture-recognition-using-mediapipe](https://github.com/jaeeun/hand-gesture-recognition-using-mediapipe)
Model Name:jaeeun
<br><img src="https://user-images.githubusercontent.com/37477845/229762360-08e05f16-cb02-45ba-a9a7-234127070ba5.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229762505-d7a224fd-9b69-4384-b0de-4201690e4c06.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229762589-7ce44e9d-bb5c-4533-8147-5592d687bbaf.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229762690-e95898ef-7465-4426-abe9-7049aa35d49e.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229762782-cef648e8-7e79-468c-bbe2-a72c271a60c2.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229763119-f8d9a3d3-3cc0-4f82-a7e6-d72208272b6a.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229763403-6b976580-47fc-4920-992a-7c870584f518.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229763450-7bb8b250-cc75-4f15-bc72-50a631262bb4.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229763676-7ba8ae46-6785-4531-a97d-70128e0c81ce.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229763827-e4ae7876-45e7-429e-a582-640ac23088f7.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229763990-0348ab03-6e64-47fe-9118-855e7ce85313.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229764123-b7911a30-3334-40cb-9ef8-2a274576dbd5.png" loading="lazy" width="250px">

## [gabesf/hand-gesture-recognition-using-mediapipe](https://github.com/gabesf/hand-gesture-recognition-using-mediapipe)
Model Name:gabesf
<br><img src="https://user-images.githubusercontent.com/37477845/229764988-8b4f4ff4-8577-423b-b4e1-d1c8182be637.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229765065-27de0ff5-7862-4195-8f9e-7ad4bb665e55.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229765137-97d6522d-efe5-4514-90c2-7a623d4e76f4.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229765223-8cc87990-a384-40cb-8f2b-9bd09ffba134.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229765298-2c8e3399-c4d8-49a5-9086-9cd14d4e3d35.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229765417-217ffae3-66af-49f7-b6cf-6ce0ef7dffc4.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229765491-85140ef2-ed87-4d03-8c50-b38fe55fc382.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229765605-37a6dcf1-f6fc-439c-9f44-2995211b13d4.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229765737-b2e761a9-bfe2-4077-85e6-df919592744a.png" loading="lazy" width="250px">

## [vjsyong/hand-gesture-recognition-mediapipe](https://github.com/vjsyong/hand-gesture-recognition-mediapipe)
Model Name:vjsyong
<br><img src="https://user-images.githubusercontent.com/37477845/229766785-a1099a30-b68f-4ad2-9e2c-4e136e0afb4c.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229766825-17fb1cd7-2e79-4e25-98f1-d9f723e29c31.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229766859-1f28830e-d7f1-49c5-bfed-665c061da6bc.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229766901-f6a76765-87dd-4d5e-9a93-d41e4ec42b0d.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229766931-933f911d-a9e9-468c-9c95-9f9a6ed099e3.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229766969-1133f6e1-9158-4552-9aa6-8e2d93eb74df.png" loading="lazy" width="250px">

## [sanghabahn/GESTURE_RECOGNINTION_MODULE](https://github.com/sanghabahn/GESTURE_RECOGNINTION_MODULE)
Model Name:sanghabahn
<br><img src="https://user-images.githubusercontent.com/37477845/229768111-7ee3eae7-a88a-40d6-9fd4-7f4922eb8e30.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229768168-4ff78c9a-27d6-40ec-8560-ecf1a4acac92.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229768205-06aaf0f7-5a36-4c3e-b4b8-a1b72ace0c0d.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229768342-2b6a207f-2870-469c-a111-f89699f1354d.png" loading="lazy" width="250px">　

## [DiaboloKiat/hand-gesture-recognition-using-mediapipe](https://github.com/DiaboloKiat/hand-gesture-recognition-using-mediapipe)
Model Name:DiaboloKiat
<br><img src="https://user-images.githubusercontent.com/37477845/229769255-a58f2345-f49b-4747-a88f-d16ccd2cf8e1.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229769317-5198b65e-d97b-4afd-82a4-a0b46d237693.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229769424-4dd44086-54a7-40a5-856a-6f8db1cf70ae.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229769488-b8e1bab8-d639-4029-8a5e-75f5c611bb39.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229769549-3adaad69-3c19-405d-a661-d2b54ca9c155.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229769701-fae92a3e-6576-40af-b94b-76a7f782dd3b.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229769805-45115d16-e805-458b-8b30-897126723633.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229769915-667077a4-71e6-4b62-b722-655e71308ea5.png" loading="lazy" width="250px">　
<img src="https://user-images.githubusercontent.com/37477845/229770039-b28c3bb8-b9a2-4c42-b03a-32f44b1c4028.png" loading="lazy" width="250px">
<br><img src="https://user-images.githubusercontent.com/37477845/229770161-a130c624-edeb-4bac-8e9f-97a51de45af5.png" loading="lazy" width="250px">　

<!--
## []()
Model Name:
<br><img src="" loading="lazy" width="250px">　
<img src="" loading="lazy" width="250px">　
<img src="" loading="lazy" width="250px">
-->

# Other 
* [rafa84fo/Facial-emotion-recognition-using-mediapipe](https://github.com/rafa84fo/Facial-emotion-recognition-using-mediapipe)

# Reference
* [MediaPipe](https://mediapipe.dev/)
* [Kazuhito00/mediapipe-python-sample](https://github.com/Kazuhito00/mediapipe-python-sample)
* [Kazuhito00/hand-gesture-recognition-using-mediapipe](https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe)

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)

# License
hand-keypoint-classification-model-zoo is under [Apache v2 license](LICENSE).
