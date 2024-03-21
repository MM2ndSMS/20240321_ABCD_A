# 20240321_ABCD_A
## Quiz numbers 리스트의 항목 중 짝수인 것만 필터링해서 result에 저장한 후 출력하세요/ numbers = [111, 26, 37, 48]
numbers = [111, 26, 37, 48]
result = list(filter(lambda x: x % 2 == 0, numbers))
print("짝수", result)
