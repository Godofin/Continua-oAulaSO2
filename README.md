# Continuação Aula SO2

## Passo a Passo Máquina Servidor

1. Entrar no Gerenciador do Servidores;
2. Clicar adicionar funções e recursos;
3. Assistente de Adição e funções de recurso;
    1. Antes de começar:  Próximo;
    2. Tipo de instalação: Instalação baseada em função ou recurso;
    3. Seleção de servidor: Próximo;
    4. Função do servidor: Serviços de Domínio do Active Directory;
        1.  Adcionar Recursos
        2.  Instalar Servidor DNS
    5. Recursos: Próximo;
    6. AD DS: Próximo;
    7. Confirmação: 
        1. Não flegar reiniciar;
        2. Instalar;
    8. Recursos: Fechar;
    9. AD DS
        1. Alerta: Configuração necessária: Clicar em mais
        2. Promover servidor a um controlador de domínio
        3. Adcionar uma nova floresta: `santo.local` -> Próximo
            1. Deixar Padrão
            2. Adicionar senha: Fatec@2022
            3. Próximo
        4. Opções DNS: Próximo
        5. Opções Adcionais NTBIOS: Próximo
        6. Caminhos: Manter padrão
        7. Examinar opções: Próximo
4. Usuarios de computadores do active Directory;
    1. Users
    2. Criar usuário e senha
    3. Senha nunca expira
    4. Criar um grupo Financeiro
    5. Adicionar pessoas a um grupo
    6. C:\ mkdir compartilhada
    7. Compartilhar pasta com o grupo financeiro

# Passo a passo Máquina Cliente

1. Abrir c\: Painel de Controle\Sistema e Segurança\Sistema
2. Mudar o nome da máquina
3. 
