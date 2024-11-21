#이진 탐색
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1

# 실험
numbers = [1, 3, 5, 7, 9, 11, 13, 15, 17, 19]
target = 7
result = binary_search(numbers, target)

if result != -1:
    print(f"숫자 {target}는 인덱스 {result}에 있습니다.")
else:
    print(f"숫자 {target}는 리스트에 없습니다.")
