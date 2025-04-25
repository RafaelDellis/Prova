# Prova

1-D

3-
const banco = []
banco.push("Flávia", "Maria", "Gabriel")
console.log("Pessoas:", banco)

banco.shift()
banco.shift()
banco.shift()
console.log(banco)

4-
const devoluções = []

const livro = {
    titulo = "sla",
    autor = "joão",
    atrasado = "s",
}


const livro2 = {
    titulo = "blah",
    autor = "maria",
    atrasado = "n"
}

const livro3 = {
    titulo = "sla",
    autor = "joão",
    atrasado = "s",
}

devoluções.push(livro, livro2, livro3)
console.log(devoluções)


5-
let idade= 30
if(idade < 12) {
    console.log("Tipo de ingresso: [Infantil].")
}

else if(idade<=  17){
    console.log("Tipo de ingresso: [Adolescente].")
}


else if(idade <= 59) {
    console.log("Tipo de ingresso: [Adulto].")
}

else if(idade>59){
    console.log("Tipo de ingresso: [Sênior].")
}
