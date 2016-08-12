DESCRIÇÃO
-----------------------------------------
Helper para escrever números e moeda por extenso, tanto no feminino quanto no masculino.

INSTALAÇÃO
-----------------------------------------
Copiar o arquivo <b>numero_extenso_helper.php</b> para a pasta <b>helpers</b> da aplicação e carregá-la no <b>__construct</b> ou <b>autoload</b>.

USO
-----------------------------------------
A função aceita três parâmetros, <b>$valor</b>(decimal,int,float), <b>$moeda</b>(boolean) e <b>$flexão</b>(boolean). Definir TRUE para moeda irá escrever reais e centavos, definir TRUE na flexão irá escrever o valor no feminino.

<em>Exemplo de uso</em>:

<b>echo $this->formata_valor(10000.00,FALSE,FALSE)</b>;

//retornará (Dez mil);

<b>echo $this->formata_valor(10000.00,TRUE,FALSE)</b>;

//retornará (Dez mil reais);

