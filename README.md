Gestão de Hotel com Threads
Neste repositório, você encontrará um algoritmo avançado que realiza a gestão simultânea de diversas operações de um hotel utilizando threads. O sistema foi projetado para simular as interações dinâmicas entre diferentes elementos de um hotel, garantindo eficiência e validação adequada para cada cenário.

Funcionalidades do Sistema
O algoritmo abrange os seguintes aspectos da gestão de um hotel:

Gestão da Recepção:

Valida e registra novos hóspedes.
Garante que os quartos sejam atribuídos de forma eficiente e com base na disponibilidade.
Gestão de Quartos:

Acompanha o estado dos quartos (ocupado, vago, em limpeza).
Garante que não haja conflitos no uso dos quartos.
Gestão das Camareiras:

Coordena as camareiras para realizar a limpeza apenas em quartos vagos.
Impede que a limpeza seja realizada enquanto há hóspedes no quarto.
Sincronização com Threads:

As operações são realizadas simultaneamente, garantindo a sincronização e evitando condições de corrida.
Destaques Técnicos
Uso de Threads:
A lógica é altamente paralela, com threads dedicadas para cada processo (hóspede, camareira, recepcionista).
Garantia de sincronização e controle por meio de travas e semáforos.
Validações Automatizadas:
Verificação em tempo real se o quarto está ocupado antes de permitir o acesso da camareira.
Bloqueio automático de novos hóspedes para quartos já em uso ou em limpeza.
