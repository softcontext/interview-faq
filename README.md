# 팀장이 최초 프로젝트 생성 시 수행하는 작업

## 1. 작업폴더 및 파일 생성
```bash
mkdir interview-faq
cd interview-faq
echo "# interview-faq" >> README.md
```

## 2. 로컬 저장소 생성
```bash
git init
```

## 3. 백업
```bash
git add --all
git status
git commit -m "first commit"
git log
```

## 4. 원격저장소 등록(연결)
```bash
git remote add origin https://github.com/softcontext/interview-faq.git
git remote -v
```

## 5. 로컬 저장소 ==업로드==> 원격 저장소
```bash
git push -u origin master
```

## 6. 팀원에게 접근권한을 부여
```
깃헙 원격 저장소 >> settings >> collaborators
>> Search by username, full name or email address
```

# 팀장이 프로젝트 중간에 수행하는 작업

## 1. 작업폴더 및 파일 생성
에디터로 수행하는 작업

## 2. 백업
```bash
git add --all
git commit -m "first commit"
```

## 3. 로컬 저장소 ==업로드==> 원격 저장소
등록된 원격 저장소가 하나일 때 간단하게 업로드가 가능하다.

```bash
git push
```

push를 거부하는 경우에 대처방법은 먼저 pull을 수행하고 그 후 push 하는 것이다.

```bash
git pull
git push
```

**************************

# 팀원이 최초 수행하는 작업

## 1. 작업폴더 및 파일 생성
이미 팀장이 수행했으므로 팀원은 팀장의 작업결과물을 가져오면 된다.

```bash
mkdir member-git
cd member-git
git clone https://github.com/softcontext/interview-faq.git
```

# 팀원이 프로젝트 중간에 수행하는 작업

## 1. 작업폴더 및 파일 생성
에디터로 수행하는 작업

## 2. 백업
```bash
git add --all
git commit -m "first commit"
```

## 3. 로컬 저장소 ==업로드==> 원격 저장소
등록된 원격 저장소가 하나일 때 간단하게 업로드가 가능하다.

```bash
git push
```

push를 거부하는 경우에 대처방법은 먼저 pull을 수행하고 그 후 push 하는 것이다.

```bash
git pull
git push
```

**************************

# 실습 과제

1. `이력서 및 자기소개서 작성`  
자신의 상태를 아는 것이 먼저입니다.

2. `선호 근무여건 결정`  
사람마다 좋아하는 음식이 다르듯이 사람마다 선호하는 근무환경 또한 다릅니다. 러프하게나마 자신이 선호하는 근무여건을 고민해 보셔야 합니다.

3. `취업 사이트 조사`  
여러 취업 사이트를 조사해서 지원하고 싶은 회사를 찾아보세요.

4. `지망 회사 선택`  
지망하고자 하는 회사를 선택하셨다면 기술면접 준비를 할 차례입니다.

5. `기술면접 예상질문 작성`  
기술면접 자료를 검색하거나 직접 작성해 봅시다.

6. `깃헙 업로드`  
팀원들과 협력하여 원하는 회사에 취업할 수 있도록 자료를 공유하고 같이 스터디를 진행해 보세요.
