# FakeLight


---

## Demo

<img width="100" height="300" alt="Image" src="https://github.com/user-attachments/assets/dae42aa3-bd0e-4a72-93ed-7455e4a0a675" />

---

## Tech Stack

- Universal Render Pipeline (URP)
- Shader graph

---

## Features

View Direction과 Surface Normal의 내적(N·V)을 이용해 Custom Fresnel을 계산하고,
Power 연산으로 Edge Falloff를 조절하여 카메라 각도에 따라 가장자리의 빛이 자연스럽게 강조되도록 구현했습니다.
<img width="1765" height="734" alt="Image" src="https://github.com/user-attachments/assets/013ce256-f46b-4fad-ba3d-3381a1699442" />

원뿔 메쉬의 UV Y 좌표를 이용하여 높이 방향 그라데이션을 생성하고, Fade 파라미터로 감쇠 범위를 조절할 수 있도록 구현했습니다.
이를 통해 광원으로부터 멀어질수록 빛의 세기가 점진적으로 감소하는 볼류메트릭 조명과 유사한 효과를 구현했습니다.
<img width="601" height="299" alt="Image" src="https://github.com/user-attachments/assets/8dad4ca5-c25e-48ce-a819-770bea46120a" />

### 


