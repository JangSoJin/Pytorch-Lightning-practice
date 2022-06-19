> # Pytorch-Lightning-practice
>
>> ### _[Repository Description]_ ('22. 6/19~)
>>  
>> - tensorflow, keras 경험은 있으나, pytorch lightning 은 처음 경험해보기에, 우선 간단한 예제만 training --> test 수행
>> - MNIST 예제를 활용하여 돌려봄
>>
>> ## MNIST EXAMPLE
>>
>> #### [DAY 1] 예제 그대로 돌려본 후, epoch 수에 따라 결과 비교 (1 vs 10)
>> - lr : 2e-4
>> - Dropout 0.1
>> - Optimizer : ADAM
>> - batch_size : 128
>> - epoch : 1
>>
>> ##### ⭐️ Test Result ⭐️ 
>> | Epoch | Result | |
>> | ------ | -- | -- |
>> | 1 | 90.74% | ![스크린샷 2022-06-19 오후 5 12 30](https://user-images.githubusercontent.com/18066248/174471983-c4db5459-468e-4e65-b0d6-154f9c6d7911.png)|
>> | 10 |  |
>> 
