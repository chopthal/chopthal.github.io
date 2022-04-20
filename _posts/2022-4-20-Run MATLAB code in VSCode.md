---
layout: post
title: Run MATLAB code in VSCode
---

### Matlab code 실행

- Matlab Interactive Terminal

  - https://github.com/apommel/vscode-matlab-interactive-terminal
  - 2022.04.07 기준
    - Matlab 2022a
    - Python 3.8.8

  1. Extension 설치
     ![_config.yml]({{ site.baseurl }}/images/matlab1.png)
  2. Version에 맞는 python 설치 (PATH에 추가)

  3. MATLAB Engine API for Python 설치 (관리자 권한 필요)

     ```
     cd "matlabroot\extern\engines\python"
     python setup.py install
     ```

  4. vscode shorcut 등록
     - 파일 - 기본설정 - 바로가기 키  
        ![_config.yml]({{ site.baseurl }}/images/matlab2.png)
