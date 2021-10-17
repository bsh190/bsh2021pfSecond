# 5~7주(9월29일 ~ 10월19일)

## 1. gltf모델의 node, mesh, primitive를 추출하여 vertices, indices 드로우 완료

![result-1](1.gif)

#### 1) [tinygltf](https://github.com/syoyo/tinygltf)
#### 2) [SaschaWillems의 tinygltf 예제](https://github.com/SaschaWillems/Vulkan-glTF-PBR)
#### 3) [사용한 gltf 모델](https://skfb.ly/6YZNJ)

## 2. gltf모델의 material, texture를 추출하여 vertices, indices 드로우에 descriptorSets 적용 완료

![result-2](2.gif)

#### 1) 1번에서 완성할 수 있었으나, 접근법이 달라 1번에서는 적용하지 못했었음. 
#### 2) 그러나 새로운 접근법을 적용하니 제대로 적용됨.
#### 3) 접근법의 변화

###### - ![#ff0000]noed→mesh→primitive→material... 순으로 접근하여 적용 (실패)
