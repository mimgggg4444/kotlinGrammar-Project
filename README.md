# kotlinGrammar-Project


!! -> null이 오면 안됨

.. -> 1~5까지

downTo -> 위에서 아래로 계산

var - 변수, val - 상수

Int, Long, Float, Double, Boolean, Char, String

val grade = if (score >= 90) "A" else if (score >= 80) "B" else "C"

val score = 88
val grade = when {
    score >= 90 -> "A"
    score >= 80 -> "B"
    else -> "C"
}

for (i in 1..5) print(i) // 1 2 3 4 5

var i = 1
while (i <= 5) {
    print(i++)
}

널 가능성 - ?

함수의 반환 타입은 함수의 선언부에서 함수 이름과 매개변수 리스트 이후에 콜론(:)을 사용하여 명시합니다
