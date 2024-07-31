# 더치 Dutch

---

복잡하고 귀찮았던 정산, 이제 더치로 깔끔하고 확실하게 해결하세요!

## Team

---

**고려대학교 컴퓨터학과 22학번 안지형**

[ahnji0520 - Overview](https://github.com/ahnji0520)

**성균관대학교 인공지능융합전공 22학번 박종민**

[jongminpark88 - Overview](https://github.com/jongminpark88)

[발표자료_제주도 여행](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/76b0deed-5709-49ca-b3d2-5348b592fad3/Untitled.pdf)

## Tech Stack

---

- **Frontend** : Java
- **Backend(server)** : Fastapi
- **Database** : MongoDB
- **IDE** : Android studio, vscode

## Details

---

### Splash & Login

---

![KakaoTalk_20240731_212526091_14.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/8aad92a7-be1c-4630-9285-2f039bb624e4/KakaoTalk_20240731_212526091_14.png)

- 앱을 실행하면 바로 로그인 안내 화면(splash 화면)이 뜹니다.
- 카카오 로그인을 지원합니다.

### Tab1 : Friends

---

![KakaoTalk_20240731_212526091.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/30019f33-257b-42a0-91e6-bc45c50671a2/KakaoTalk_20240731_212526091.png)

![KakaoTalk_20240731_212526091_02.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/e1fba6b5-6d76-4e92-b67c-3bda974dd422/KakaoTalk_20240731_212526091_02.png)

![KakaoTalk_20240731_212526091_03.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/b642992d-e621-463b-a716-3230a30c3c59/KakaoTalk_20240731_212526091_03.png)

![KakaoTalk_20240731_212526091_04.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/3417a26d-be78-441d-b7b9-a3903eb90eac/KakaoTalk_20240731_212526091_04.png)

![KakaoTalk_20240731_212526091_05.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/dd86341c-01fd-426a-aec4-369de7a52220/KakaoTalk_20240731_212526091_05.png)

![KakaoTalk_20240731_212526091_06.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/8caca8e1-2965-4ea6-a557-68852bfd51b9/KakaoTalk_20240731_212526091_06.png)

친구들과의 정산 목록을 확인할 수 있는 탭입니다.

- 친구의 카카오 프로필상 이름과 간단하게 정리된 채무관계를 확인할 수 있으며,

<aside>
💡 간단하게 정리된 채무관계란 **두 사람 간에** 여러 채무 내역이 있을 경우 합산하여 **하나의 채무 관계**로 변환한 것을 의미합니다.

</aside>

- 정산이 완료된 친구들은 뜨지 않습니다.
- 해당 정산 목록에 들어가면, 세부 채무 내역을 확인할 수 있고
- 정산 후 정산하기 버튼을 누르면 정산이 완료되며 채무관계가 사라집니다.
- 하단의 플로팅 버튼(+)을 통해 지출을 추가할 수 있습니다.

### Tab2 : Group

---

![KakaoTalk_20240731_212526091_08.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/8fa8a41f-374a-46da-bc5d-65f1c03bf00a/KakaoTalk_20240731_212526091_08.png)

![KakaoTalk_20240731_212526091_07.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/f7076151-2a6b-40b9-b815-de9e9e472cdf/KakaoTalk_20240731_212526091_07.png)

![KakaoTalk_20240731_212526091_09.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/899fd2fc-6dd5-49bc-8a21-691a5560d32a/KakaoTalk_20240731_212526091_09.png)

![KakaoTalk_20240731_212526091_10.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/82e74696-b54f-4381-b7fc-8e13bfcf3f84/KakaoTalk_20240731_212526091_10.png)

![KakaoTalk_20240731_212526091_11.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/399e7258-4970-4b5c-a6b2-e1089153cb2e/KakaoTalk_20240731_212526091_11.png)

내가 속해있는 그룹을 보여주고, 그룹 안에서 생긴 채무 관계를 정리해서 보여주는 탭입니다.

- 내가 속해 있는 그룹들을 리스트로 보여줍니다.
- 그룹을 클릭해서 들어가면 그룹의 지출 내역을 보여줍니다. ( 정산을 완료해도 이 지출 내역은 남아있도록 설계했습니다.)
- 그룹 내에서 복잡했던 채무관계를 더 간단한 채무관계로 변환해줍니다.

<aside>
💡 더 간단한 채무관계란 3인 이상의 사람들의 채무관계 간에 순환관계가 생길 경우 이를 이용하여 더 간단하게 만든 채무관계입니다.

</aside>

<aside>
💡 a가 b에게 1000원을 갚아야 하고 b가 c에게 1000원을 갚아야 할 경우, a가 c에게 1000원을 주는 것으로 돈계산을 끝내는 경우를 생각해보시면 됩니다.

</aside>

<aside>
💡 그래프 리덕션 알고리즘을 사용하였습니다.

</aside>

### Tab3 : Profile

---

![KakaoTalk_20240731_212526091_01.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/3eaddc90-528b-4fb7-a927-2250610babda/KakaoTalk_20240731_212526091_01.png)

![KakaoTalk_20240731_212526091_12.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/c5c77dfd-22a4-4ab1-b784-f2cd74e977b6/KakaoTalk_20240731_212526091_12.png)

연동된 카카오톡 프로필과 닉네임, 내 소비내역 차트를 보여주는 탭입니다.

- 카카오톡에서 불러온 프로필 사진과 닉네임을 보여주고,
- 내 소비내역을 카테고리별로 정리하여 차트로 시각화해줍니다.



