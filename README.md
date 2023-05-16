# 사칙연산 우선순위😊

**사칙연산은 덧셈, 뺄셈, 곱셈, 나눗셈의 4가지 연산을 말합니다.** 사칙연산을 할 때는 다음과 같은 순서로 계산해야 합니다.

1. **괄호가 있는 경우 괄호 안의 연산을 먼저 수행**합니다. 괄호가 중첩된 경우 가장 안쪽의 괄호부터 수행합니다.
2. **거듭제곱이 있는 경우 거듭제곱을 먼저 수행**합니다.
3. **곱셈과 나눗셈이 있는 경우 곱셈과 나눗셈을 먼저 수행**합니다. 곱셈과 나눗셈은 우선순위가 같으므로 왼쪽에서 오른쪽으로 순서대로 계산합니다.
4. **마지막으로 덧셈과 뺄셈을 수행**합니다. 덧셈과 뺄셈도 우선순위가 같으므로 왼쪽에서 오른쪽으로 순서대로 계산합니다.

**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

예를 들어, $`2+3×(4-2)^2÷2`$ 라는 식을 계산한다면 다음과 같이 진행할 수 있습니다.
- 괄호 안의 연산을 먼저 수행합니다. $4 - 2 = 2$ 이므로, 식은 $2 + 3 × 2^2 ÷ 2$ 로 바뀝니다.
- 거듭제곱을 먼저 수행합니다. $2^2 = 4$ 이므로, 식은 $2 + 3 × 4 ÷ 2$ 로 바뀝니다.
- 곱셈과 나눗셈을 먼저 수행합니다. 왼쪽에서 오른쪽으로 순서대로 계산하면, $3 × 4 = 12$ 이고, $12 ÷ 2 = 6$ 이므로, 식은 $2 + 6$ 으로 바뀝니다.
- 마지막으로 덧셈을 수행합니다. $2 + 6 = 8$ 이므로, 식의 최종 결과는 8 입니다.


**음수를 포함한 사칙연산 😊**

**음수는 0보다 작은 정수**를 말합니다. 음수는 $-$ 기호로 표시하며, 예를 들어 $-3, -5, -10$ 등이 있습니다. 음수는 수직선에서 $0$의 왼쪽에 위치하며, 절댓값이 작을수록 크다고 합니다. 예를 들어 $-3$은 $-5$보다 큽니다.

음수의 사칙연산은 다음과 같은 규칙을 따릅니다.
- **덧셈: 같은 부호의 음수를 더하면 부호는 그대로이고 절댓값을 더합니다.** 예를 들어, $-3 + (-5) = -8$ 입니다. 다른 부호의 음수를 더하면 부호는 절댓값이 큰 수의 부호이고 절댓값은 큰 수에서 작은 수를 뺍니다. 예를 들어, $-3 + 5 = 2$ 입니다.
- **뺄셈: 음수에서 음수를 빼면 덧셈과 반대로 합니다.** 즉, 같은 부호의 음수를 빼면 부호는 절댓값이 큰 수의 부호이고 절댓값은 큰 수에서 작은 수를 뺍니다. 예를 들어, $-3 - (-5) = 2$ 입니다. 다른 부호의 음수를 빼면 부호는 그대로이고 절댓값을 더합니다. 예를 들어, $-3 - 5 = -8$ 입니다.
- **곱셈: 음수와 음수를 곱하면 양수가 됩니다. 즉, 부호는 다르면 음수이고 같으면 양수입니다.** 절댓값은 그냥 곱합니다. 예를 들어, $-3 × (-5) = 15$ 입니다. $-3 × 5 = -15$ 입니다.
- **나눗셈: 음수와 음수를 나누면 양수가 됩니다. 즉, 부호는 곱셈과 마찬가지로 다르면 음수이고 같으면 양수입니다.** 절댓값은 그냥 나눕니다. 예를 들어, $-15 ÷ (-5) = 3$ 입니다. $-15 ÷ 5 = -3$ 입니다.

음수의 사칙연산을 할 때는 다음과 같은 몇 가지 **주의사항**이 있습니다.
- **0으로 나눌 수 없습니다. 0으로 나누는 것은 의미가 없는 연산이므로 정의되지 않습니다.** 예를 들어, $3 ÷ 0$ 또는 $(-5) ÷ 0$ 은 계산할 수 없습니다.
- **음수를 거듭제곱할 때는 지수의 홀짝에 따라 부호가 달라집니다. 음수를 짝수 제곱하면 양수가 되고, 음수를 홀수 제곱하면 음수가 됩니다.** 예를 들어, $(-2)^2 = 4$ 이고, $(-2)^3 = -8$ 입니다.
- **음수를 분수로 나타낼 때는 부호를 분자나 분모 중 하나에만 붙여야 합니다.** 부호를 둘 다 붙이면 양수가 되므로 틀린 표현입니다. 예를 들어, $\frac{- 3}{4}$, $\frac{3}{-4}$ 또는 $-\frac{3}{4}$는 올바른 표현이지만, $\frac{-3}{-4}$ 는 잘못된 표현입니다.
