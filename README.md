# Validador de CPF em PHP

## Descrição
Esta função PHP tem como objetivo validar a autenticidade de números de CPF (Cadastro de Pessoa Física) brasileiros. Ela utiliza os algoritmos de validação padrão para garantir a integridade dos dados.

exemplo de como chamar a função


$cpf = "111.112.111-13";

if(validarCPF($cpf)){

echo "cpf válido";
}else{
    echo "cpf inválido";

}
