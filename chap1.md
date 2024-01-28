# Introduction

## Motivation

우리가 만드는 모든 것에는 구조가 있음  
우리가 만드는 것에 더 투자할 수록, 추후 그 구조를 바꾸기 쉽지 않아짐  


그렇다면 구조가 중요한 이유는?
- 구조는 우리가 만드는 제품의 의도를 나타냄 -> 우리가 만드는 sw는 구조에 따라 다른 특성을 가짐  
  - 그리고 이는 sw의 성능과 규모에 영향을 끼치고, 새로운 기능을 쉽게 추가할 수 있을지의 여부도 판단함  
  - 보안에도 영향을 끼침
- 그리고 다시 구조를 디자인하는 데에는 많은 시간과 돈이 듬


## Definition

software architecture 의 정의는?
- high level description of the system's structure, its different components and how those components communicate with each other to fulfill the system's requirements and constraints

- 시스템의 구조를 추상화하여 표현하며(세부적으로 어떤 프로그래밍 언어와 프레임워크를 사용할지를 결정하는 것이 아니라, 더 높은 추상화 된 레빌의 구성요소를 다룸)  
- 구성요소들이 어떻게 상호작용하는 지를 나타냄
- 그리고 요구조건과 제약조건을 충족해야함

추상화의 레벨
- 다양한 추상화 레벨을 가질 수 있음
  - classes, structs
  - modules, package, libraries
  - services(processes/group of processes) <- 위 강의에서는 이 레벨에서 설명할 것임

분산된 서비스들의 장점
- 많은 양의 요청을 처리할 수 있음
- 많은 양의 데이터를 처리하고 저장할 수 있음
- 많은 수의 사용자를 받아들일 수 있음

## Software Development Cycle

소프트웨어 개발은 4단계로 나뉨. 일반적으로 아래 4단계가 반복되어 수행되면서 sw가 점진적으로 개선됨. 그렇기에 첫번째 사이클이 매우 중요함  
`Design -> Implementation -> Testing -> Deployment `  
본 강의에서는 Design 단계의 결과 즉 Implementation 단계의 입력값을 만드는 것에 집중할 것임  


software architecture 의 경우 정량적인 기준이 없어, 잘 설계되었는지 판단하기 힘들지만. 일반적으로 아래의 방법들을 고려할 수 있음
- 체계적인 설계 과정을 따랐는가
- architecture pattern 에 부합하는가
- best practices 와 유사한가


