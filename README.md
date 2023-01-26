### Redes II - 2023
### Trabalho prático de Rede II - Enunciado do trabalho

## INTRODUÇÃO

Este trabalho permitirá aos alunos ganhar competências no planeamento, configuração e
manutenção de redes locais comutadas, usando routers, switches e pontos de acesso sem fios, com
especial incidência nas tecnologias de switching, e envolverá o uso de diversas tecnologias de rede
(Ethernet, VLAN, STP, EtherChannel, DHCP, FHRP, segurança e WLAN, entre outras).
O trabalho será, preferencialmente, de realização em grupo de 2 elementos


A empresa MBF (Meia Bola e Força, lda.), com atuação na área do desporto, estabeleceu a
sua sede em Mirandela para aproveitar os profissionais de superior qualidade formados na EsACT.
2/4
O referida sede fica situada num edifício com três pisos, cada um com cerca de 300 m2
.
Existem dois departamentos (Comercial e Operacional), havendo trabalhadores de cada
departamento em todos os pisos.
A empresa solicitou o planeamento da sua rede local tendo em consideração os requisitos que
se encontram descritos a seguir.
Requisitos gerais
• Em cada um dos pisos haverá uma sala de equipamentos onde estarão alojados os
equipamentos de rede.
• Há 60 tomadas de rede por piso, mas inicialmente apenas irão ser utilizadas cerca de 15.
• Bastará haver apenas o número de equipamentos de rede adequados ao número de
utilizadores atuais. No entanto, a rede deverá ser escalável para permitir o fácil incremento
de utilizadores.
• A rede cablada deverá suportar a divisão do tráfego IP pelos diferentes departamentos
existentes (dois de momento, Dep. Comercial e Dep. Operacional).
Endereçamento IP
• A rede deverá suportar IPv4 e IPv6.
• Os equipamentos de rede deverão ter configurações estáticas de endereços.
• As configurações de rede dos PCs e restantes dispositivos terminais deverão ser obtidas de
forma automática.
◦ Para tal, sempre que possível utilize as funcionalidades dos equipamentos de rede e evite
recorrer a servidores externos.
◦ Reserve alguns endereços em cada rede para atribuição estática.
◦ A duração da concessão deverá ser de 12 horas.
Gestão e Manutenção dos equipamentos
• Para facilitar a gestão dos equipamentos de rede, todos deverão ter convenientemente
configurados com nome e descrição das interfaces de backbone.
Desempenho e redundância
• Deverá minimizar o tempo de convergência da rede.
• Os PCs que se liguem à rede deverão poder comunicar o mais rapidamente possível.
• Os pontos de estrangulamento de tráfego deverão ser minimizados, promovendo ligações
com maior largura de banda sempre que possível.
• Deverá ter-se em consideração que o switch de distribuição não deverá ter portas bloqueadas
devido ao STP.
• Considere a possibilidade de implementar gateways redundantes.


## SEGURANÇA

• Promova a segurança do acesso aos equipamentos de rede, quer localmente quer
remotamente.
• Promova a segurança da rede local. Configure os switches para mitigar ataques, incluindo
às interfaces, tabela de endereços MAC, VLAN, DHCP, ARP, STP e CDP.
Rede sem fios
• Implemente uma rede sem fios para os utilizadores da empresa.
• O acesso à rede sem fios apenas deverá ser permitido após autenticação dos utilizadores
com as suas credenciais.
Acesso à Internet
• Simule a ligação da rede da empresa à Internet. Na Internet implemente, pelo menos:
◦ Um servidor Web, com o nome registado no servidor de DNS.
◦ Um servidor DNS, a utilizar pelos utilizadores da empresa.
• Utilize encaminhamento IP estático.
Configurações adicionais
• Configurações adicionais serão valorizadas.
Protótipo e Testes
• Deverá implementar-se um protótipo da rede em simulador (Ex.: PacketTracer).
• O protótipo deve ter, no mínimo:
◦ um dispositivo terminal por VLAN em cada piso
◦ um utilizador da rede sem fios ligado a cada AP.
Testes
• Faça os testes necessários para garantir a conetividade na rede. Verifique, nomeadamente,
se:
◦ Os PCs conseguem comunicar entre si.
◦ Os PCs conseguem comunicar com a Internet.
◦ As medidas de segurança implementadas estão a funcionar.
◦ A tolerância a falhas implementada funciona.


## DOCUMENTAÇÃO (RELATÓRIO)

• A documentação é essencial para garantir uma manutenção adequada de uma rede pois
simplifica a identificação e a resolução de problemas e facilita as intervenções na
infraestrutura. Deverá ser criada a documentação da rede que contenha:
◦ Desenho lógico da rede, com indicação das redes existentes e interligação das mesmas.
◦ Desenho físico da rede, com indicação dos equipamentos existentes e das suas ligações.
◦ Tabela de subredes IP, com indicação para cada uma do endereço IP, máscara de subrede,
gateway predefinido, gama de endereços válidos e gamas de endereços para atribuição
dinâmica.
◦ Tabela dos equipamentos de rede com indicação, para cada um, do nome, tipo de
equipamento, marca, modelo e endereço IP das interfaces.
◦ As configurações dos equipamentos (basta uma configuração por tipo de equipamento,
em ficheiro de texto).
• Documente ainda o estado dos equipamentos, nomeadamente:
◦ Routers (basta um):
▪ Tabelas de encaminhamento;
▪ Resumo das interfaces (estado e endereço IP);
▪ Resumo das atribuições de endereços via DHCP;
◦ Switches (basta um de acesso e um de distribuição):
▪ Resumo das VLANs existentes e associação às portas;
▪ Informações relacionadas com a segurança
• Indicação dos testes efetuados para garantir o funcionamento da rede da forma pretendida.
