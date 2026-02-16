# QA-DSA--2-SearchElement

function EvenArray(Arr,Searchele) {
    for (let i = 0; i < Arr.length; i++){
        if (Arr[i] == Searchele) {
           console.log("Found Your Element:",i) 
        } else {
            console.log("Found Your Element:", -1)
            break 
        }
    }
}

EvenArray([2,3,6,7,20],2)
