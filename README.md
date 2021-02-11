# FlipAnimation

CSS를 이용해 Flip 효과를 만들어 보았습니다.

![FlipAnimation](https://user-images.githubusercontent.com/61913417/107606735-61598a00-6c7a-11eb-85b5-7196c99642f8.gif)

### 공부
transform: rotateX(180deg)와 transform: rotateX(360deg)를 통해 한 바퀴 돌려주는데  
perspective를 주지 않으면 원근감이 없어 2D 상태에서 돌아가는 것 처럼 보이므로  
perspective: 400px;값을 이용해 원근감을 주어 3D 효과가 잘 나타나게 만들어 준다!
