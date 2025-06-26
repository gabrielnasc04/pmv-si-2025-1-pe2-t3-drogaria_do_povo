# Código do projeto

Código do projeto, exportado da ferramenta Sydle One.

if(_pin.tipoDeSolicitacao === "Cadastro de Produtos"){
    return true;
}
else {
    return false;
}

if(_pin.tipoDeSolicitacao === "Retirada de produtos do Estoque"){
    return true;
}
else {
    return false;
}

_object._executor = _pin._requestor;
