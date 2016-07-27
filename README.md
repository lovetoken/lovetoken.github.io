# Readme

저의 블로그 호스팅을 위한 Github 저장소 입니다.
사용하는 템플릿은 [Jekyll Themes](http://jekyllthemes.org/) 에서 선택한 [Stack Problems](https://github.com/agusmakmun/agusmakmun.github.io) 테마를 이용 하였습니다.

# 내가 유념해야할 사항들 정리

## Markdown parser

Markdown parser 는 Github pages 에서 기본으로 하는 Kramdown 을 기준으로 합니다.
따라서 기존에 사용했던 Markdown parser 인 Pandoc 과 다르게 LaTeX 수식을 적용시키기 위해서 자바스크립트가 추가적으로 들어가게 되며 `$ ... $` 양식이 호환되지 않고 (`$$ ... $$` 만 가능) table 역시 기존것과 호환되지 않습니다.