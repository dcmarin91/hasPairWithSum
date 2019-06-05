# Ejercicio Google

## Implementacion funcion Suma 8

```
function hasPairWithSum(arr, sum) {
  let comp = {};
  for(let i = 0; i < arr.length; i++) {
    if(comp[arr[i]]){
      return true;
    } else {
      comp[sum - arr[i]] = i;
    }
  }
  return false;
}

```
