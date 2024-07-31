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

![splash](https://github.com/user-attachments/assets/d4b02abb-018a-45da-b6b1-0cfb4e15a546)

- 앱을 실행하면 바로 로그인 안내 화면(splash 화면)이 뜹니다.
- 카카오 로그인을 지원합니다.

### Tab1 : Friends

---

![tab1_ver1](https://github.com/user-attachments/assets/99dc6231-7830-4350-9d12-4cfd31fbecd7)
![add_friends](https://github.com/user-attachments/assets/4c6ba375-2842-4f75-96b1-002e0874a193)
![add_expense](https://github.com/user-attachments/assets/747ea59c-0a5b-4efb-8c8f-e404905d8a3f)

![tab1_ver2](https://github.com/user-attachments/assets/9b77a36c-4480-4d15-977c-e986eae7bcee)
![debt_detail](https://github.com/user-attachments/assets/c893e951-8d1d-4f29-ad9b-18b8252e3681)
![settled](https://github.com/user-attachments/assets/faa2f732-3cf3-42e3-b2aa-1dd4dee948db)

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

![tab2](https://github.com/user-attachments/assets/2cdcd211-1207-4748-9a70-974fb68eef52)
![add_group](https://github.com/user-attachments/assets/f9558004-1dd6-4878-bedd-0d8c40acda3c)

![group_expense](https://github.com/user-attachments/assets/b7dbfd64-0a22-4a9d-977e-935b15862dfb)
![group_debt](https://github.com/user-attachments/assets/2405df39-6427-4e1e-b024-17b6ab039426)
![group_debt_simplified](https://github.com/user-attachments/assets/a7a1623d-2423-476e-95a6-7fd2b7796c0b)
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

![tab3_ver1](https://github.com/user-attachments/assets/529a1a9a-e906-4f51-8f6e-ae34faa1bfa1)
![tab3_ver2](https://github.com/user-attachments/assets/524bdcb6-ec7e-4455-a521-03a8038233e4)
연동된 카카오톡 프로필과 닉네임, 내 소비내역 차트를 보여주는 탭입니다.

- 카카오톡에서 불러온 프로필 사진과 닉네임을 보여주고,
- 내 소비내역을 카테고리별로 정리하여 차트로 시각화해줍니다.



