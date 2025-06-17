# report
c 언어 리포트

1. 무지게 사각형을 그리는 코드를 작성하시오.

glClearColor(1.0f, 1.0f, 1.0f, 1);

배경색을 하얀색으로 설정하고

glBegin(GL_QUADS);

사각형으로 설정한 다음

glColor3f(1, 0, 0); glVertex2f(-0.5f, -0.5f);
glColor3f(0, 1, 0); glVertex2f(0.5f, -0.5f);
glColor3f(0, 0, 1); glVertex2f(0.5f, 0.5f);
glColor3f(1, 1, 0); glVertex2f(-0.5f, 0.5f);

각 정점을 지정한 후 색상을 입힌다.


2. 와이어 프레임으로 회전하는 주전자를 구현하시오.

glColor3f(0.0f, 1.0f, 0.0f);

주전자 색상을 초록색으로 설정하고

glutWireTeapot(0.5);

주전자를 와이어로 설정한다.
