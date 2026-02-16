# QA-DSA--2-SearchElement

function EvenArray(Arr, Searchele) {
    for (let i = 0; i <= Arr.length; i++) {
        if (Arr[i] == Searchele) {
            return i
        }
    }
    return -1
}

console.log(EvenArray([2, 3, 6, 7, 20], 20))
