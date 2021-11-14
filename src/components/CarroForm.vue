<template>


        <div>

            <div id="carro-form">

                <div class="input-container">

                    <label for="nome">Nome da Pessoa: </label>
                    <input type="text" id="nome" v-model="nome" placeholder="Informe o seu nome: ">

                </div>


                <div class="input-container">

                    <label for="nomeCarro">Nome do Carro: </label>
                    <input type="text" id="nomeCarro" v-model="nomeCarro" placeholder="Informe o nome do Carro ">
                    
                </div>


                <div class="input-container">

                    <label for="placaCarro">Placa do Carro: </label>
                    <input type="text" id="placaCarro" v-model="placaCarro" placeholder="Informe a placa do Carro: ">
                    
                </div>


                <div class="input-container">

                    <label for="hora">Horário de Entrada: </label>
                    <input type="text" id="hora" v-model="hora" placeholder="Informe o Horári de Entrada: ">
                    
                </div>


                <div class="input-container">

                    <input type="submit" class="submit-btn" value=" Cadastrar o Carro">
                    
                </div>




            </div>












        </div>



</template>
    

<script>


    export default {
        name: "CarroForm"
    }

</script>



<style scoped>

    #carro-form {
        max-width: 300px;
        margin: 0 auto;;
    }

    .input-container {
        display: flex;
        flex-direction: column;
        margin-bottom: 20px;
    }

    label {
        font-weight: bold;
        margin-bottom: 15px;
        color: #222;
        padding: 5px 10px;
        border-left: 4px solid #3F7FBF;
    }

    input {
        padding: 5px 10px;
        widows: 300px;
    }

    .submit-btn {
        background-color: #3F7FBF;
        color: white;
        font-weight:  bold;
        padding: 10px;
        font-size: 16px;
        border: 2px solid white;
        cursor: pointer;
        transition:  .5s;
    }

    .submit-btn:hover {
        background-color: tomato;
        font-size: 18px;
    }



</style>