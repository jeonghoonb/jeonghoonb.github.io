---
layout: post
title:  "JAVA ANNOTATION"
date:   2019-05-22
excerpt: "What is JAVA ANNOTATION ?"
tag:
- JAVA
- ANNOTATION
comments: true
---

# JAVA ANNOTATION

소스 코드에 추가하여 사용 할 수 있는 메타데이터의 일종, JDK 1.5 버전 이상에서 사용

[![java annotation](https://jeonghoonb.github.io/assets/img/post_2019/20190522_javaannotation_01.png)](https://jeonghoonb.github.io/assets/img/post_2019/20190522_javaannotation_01.png)

<br>

* 사전적으로는 '주석'이라는 의미
* 컴파일 타임 또는 런타임에 해석
* '@'와 함께 시작

<br>

## 종류

|어노테이션|설명|
|:---|:---|
|@SuppressWarnings|컴파일러가 경고하는 내용 중 제외 항목 지정|
|@Data|각 필드의 getter, setter 자동 생성|
|@Service|비즈니스 로직이 들어가는 Service로 등록|
|@Autowired|Spring DI 자동으로 설정, type으로 연결|
|@AllArgsConstructor|모든 인자의 생성자를 자동으로 생성|
|@NoArgsConstrucor|인자가 없는 생성자를 자동으로 생성|
|@Configuration|Spring IoC 컨테이너가 해당 클래스를 빈 정의의 소스로 사용|
|@Bean|Spring XML 설정의 <bean />과 동일한 기능|
|@Controller|Spring MVC의 Controller 역할|
|@RequestMapping|URL을 Class 또는 Method와 맵핑|
|@GetMapping|@RequestMapping + GET Method|
|@PostMapping|@RequestMapping + POST Method|
|@ResponseBody|HTTP Body 부분만 전달, XML, JSON 형태|
|@Api|Api의 역할 표시|
|@ApiOperation|Api의 기능 표시|
|@ApiParam|Api에서 사용할 파라미터 표시|
|@RestController|@Controller + @ResponseBody|
|@Transacntional|DB 트랜잭션 관리 용도|


#### 자료참고
* [위키백과](https://ko.wikipedia.org/wiki/%EC%9E%90%EB%B0%94_%EC%96%B4%EB%85%B8%ED%85%8C%EC%9D%B4%EC%85%98)

<center>ⓒ2019 Jeonghoon Bang</center>