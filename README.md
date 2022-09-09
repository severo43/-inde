<?php
    class Cliente{
        public $codigo;
        public $nome;
        public $cpf;
        public $endereco;
        public $telefone;
        public $email;

        public function __construct($codigo,$nome,$cpf,$endereco,$telefone,$email)
        {
            $this->codigo = $codigo;
            $this->nome = $nome;
            $this->cpf = $cpf;
            $this->endereco = $endereco;
            $this->telefone = $telefone;
            $this->email = $email;
        }
    }


    class Produto{
        public $codigo;
        public $descricao;
        public $valor;
        public $estoque;

        public function __construct($codigo,$descricao,$valor,$estoque)
        {
           $this->codigo = $codigo;
           $this->descricao = $descricao;
           $this->valor = $valor;
           $this->estoque = $estoque; 
        }

    }
    ?>

    <?php
        $cliente = new Cliente('','','','','','');
        
        $produto = new Produto('','','','');
    ?>
