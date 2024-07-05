[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WlhqwDRS)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285506&assignment_repo_type=AssignmentRepo)

## HW
> 程式碼和config是根據助教給的[colab](https://colab.research.google.com/drive/13r94i6Fh4oYf-eJRSi7S_y_cen5NYkBm?usp=sharing#scrollTo=kSGsZo3xoD4O)和[guideline](https://huggingface.co/docs/transformers/en/peft)去修改和實作的

### 資料級、參數
- 這邊訓練時，我給的資料集是"stanfordnlp/imdb"，其中1~1023training用，1024~1080做validation
- learning rate = 5e-5
- batchsize = 64

剩下的參數都是預設
### config1
![image](https://github.com/mvclab-ntust-course/course7-llm-B11115019/assets/127180001/23d9142f-8e64-4777-a337-6db176468d35)
### config2
![image](https://github.com/mvclab-ntust-course/course7-llm-B11115019/assets/127180001/88bd8708-3ff7-45f7-94ab-b201a3dd4e5e)
### config3
![image](https://github.com/mvclab-ntust-course/course7-llm-B11115019/assets/127180001/d2261464-98c5-4f90-8872-94280aa29dfd)

## 結果
### config1
![image](https://github.com/mvclab-ntust-course/course7-llm-B11115019/assets/127180001/2c5a4f4d-4118-4a9c-8138-32b5c3a8e3cb)
### config2
![image](https://github.com/mvclab-ntust-course/course7-llm-B11115019/assets/127180001/ea6f1347-8b47-413a-a396-328caed5ae86)
### config3
![image](https://github.com/mvclab-ntust-course/course7-llm-B11115019/assets/127180001/32df19aa-656c-4d5e-a414-9a6cfe0912c7)

