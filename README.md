## Identidade, Acesso e Segurança

Identidade, acesso e segurança são conceitos relacionados à proteção de informações e dados, e à garantia de que o acesso a sistemas e recursos é feito por pessoas autorizadas:

### Gerenciamento de identidade e acesso (IAM)
É uma forma de controlar quem tem acesso a dados e sistemas, e o que cada usuário pode fazer. O IAM é uma ferramenta que ajuda a fortalecer a segurança das informações corporativas, minimizando o risco de invasões e violações de dados.
### Segurança de identidade
É a prática de proteger identidades digitais contra acesso não autorizado, manipulação ou uso indevido. 
### Modelo de “Confiança zero”
É uma estratégia de segurança que se baseia na ideia de “nunca confiar, sempre verificar”. 
### Sistema de controle de acesso
É uma tecnologia que modera o acesso a ativos digitais, como redes, sites e recursos em nuvem.

## Microsoft Entra ID
O Microsoft Entra ID é um serviço de gerenciamento de identidade e acesso na nuvem que permite que os funcionários acessem recursos internos e externos, como o Microsoft 365, o portal do Azure e outros aplicativos SaaS.</br>

*O Microsoft Entra ID era anteriormente conhecido como Azure Active Directory.</br>

O Microsoft Entra ID oferece os seguintes recursos:

### Autenticação e autorização
O Microsoft Entra ID oferece serviços de autenticação e autorização para vários serviços da Microsoft.
### Identidades gerenciadas
O Microsoft Entra ID permite que objetos de aplicativo e entidades de serviço se autentiquem com uma senha ou um certificado.
### Identidade do dispositivo
O Microsoft Entra ID verifica se o dispositivo no fluxo de autenticação é legítimo e atende aos requisitos técnicos.
### Acesso à rede
O Microsoft Entra ID permite o acesso seguro à Internet, ao software como serviço e aos aplicativos do Microsoft 365.
### Funções personalizadas
O Microsoft Entra ID dá suporte a funções personalizadas, que permitem selecionar as permissões de função desejadas. 
### Grupos
O Microsoft Entra ID permite atribuir um conjunto de permissões de acesso a todos os membros de um grupo.

## Microsoft Entra Domain Services
O Microsoft Entra Domain Services (Azure AD DS) é um serviço de domínio gerenciado que fornece autenticação e gerenciamento para aplicativos e cargas de trabalho: Ingresso no domínio, Política de grupo, Protocolo LDAP, Autenticação Kerberos/NTLM.</br>
O Microsoft Entra Domain Services permite que os usuários entrem em serviços e aplicativos conectados ao domínio gerenciado usando as suas credenciais existentes.</br>

O Microsoft Entra Domain Services é parte do Microsoft Entra e oferece os seguintes benefícios:
- Economia de custos 
- Operação mais eficiente 
- Não é necessário implantar, gerir ou aplicar patches a controladores de domínio 
- Permite executar aplicativos herdados na nuvem 
- Permite realizar lift-and-shift de recursos locais para o Azure

## Autenticação e autorização
Autenticação e autorização no Azure são processos que verificam a identidade de um usuário ou aplicativo e determinam se ele tem permissão para acessar recursos:
### Autenticação
Verifica a identidade de um usuário ou aplicativo que acessa um recurso. A autenticação pode ser feita por meio de credenciais como nome de usuário e senha, certificado ou logon único (SSO).
### Autorização
Determina se um usuário ou aplicativo tem permissão para acessar um recurso específico. A autorização é geralmente feita por meio de um protocolo baseado em token, como o OAuth 2.0.

No Azure, a autenticação e autorização podem ser configuradas de várias formas, como: 
### Azure Active Directory (Azure AD)
Permite definir políticas de acesso condicional baseadas em critérios como usuário, local, dispositivo e aplicativo.
### Aplicativos de Contêiner do Azure
Fornecem recursos internos de autenticação e autorização para proteger o aplicativo. 
### Microsoft Entra ID
Provedor de identidade centralizado na nuvem que permite delegar a responsabilidade de autenticação e autorização.

## Autenticação multifator
Autenticação multifator (MFA) é um processo de login que exige que o usuário forneça mais do que apenas uma senha para acessar uma conta ou serviço. O objetivo é aumentar a segurança e dificultar o acesso não autorizado a sistemas e redes. 

A MFA pode exigir que o usuário combine vários fatores de autenticação, como: 

- Algo que o usuário saiba, como uma senha ou PIN 
- Algo que o usuário tenha, como um cartão inteligente ou chave USB 
- Algo que o usuário seja, como uma impressão digital ou reconhecimento facial

## B2C do identidades externas do azure
O Azure Active Directory B2C (Azure AD B2C) é uma solução de gerenciamento de identidade e acesso do cliente (CIAM) que permite a criação de aplicativos web e móveis: 
- O Azure AD B2C permite que os clientes acessem os aplicativos e APIs da empresa usando suas identidades de conta social, empresarial ou local. 
- O Azure AD B2C pode ser configurado para federar-se a um locatário do Microsoft Entra, permitindo que o locatário do Microsoft Entra gerencie o acesso dos funcionários aos aplicativos. 
- O Azure AD B2C permite personalizar a experiência do usuário com a marca da empresa, personalizando o HTML, o CSS e o JavaScript. 
- O Azure AD B2C oferece recursos como logon único, acesso condicional e autenticação multifator para proteger e controlar o acesso. 
- O Azure AD B2C é um serviço separado do Microsoft Entra ID, mas foi criado com a mesma tecnologia.

## Acesso Condicional do Azure
O Acesso Condicional do Azure Active Directory é uma funcionalidade que permite controlar o acesso a recursos do Azure de acordo com políticas detalhadas. 

O Acesso Condicional do Azure Active Directory, agora conhecido como Microsoft Entra ID, permite: 
- Controlar o acesso a aplicativos, dados confidenciais e sessões 
- Restringir o acesso a dispositivos vulneráveis ou comprometidos 
- Proteger os usuários e as informações corporativas 
- Garantir que apenas dispositivos seguros tenham acesso aos aplicativos

## Controle de acesso baseado em função
O controle de acesso baseado em função (RBAC) é uma técnica que define os privilégios e funções que um usuário tem para acessar recursos, redes ou sistemas. O RBAC é baseado na função do usuário dentro de uma empresa ou equipe, e garante que os usuários e computadores tenham apenas o nível de acesso que lhes pertence. 

O RBAC atribui permissões com base em:
- Acesso (o que o usuário pode ver)
- Operações (o que o usuário pode fazer)
- Sessões (por quanto tempo o usuário pode fazer)

## Microsoft Defender para Nuvem
O Microsoft Defender para Nuvem é uma plataforma de proteção de aplicativos nativos de nuvem (CNAPP) que fornece segurança para ambientes multinuvem e híbridos. 

O Defender para Nuvem oferece: 
- Gerenciamento da Postura de Segurança na Nuvem (GPSN), que ajuda a encontrar pontos fracos na configuração de nuvem 
- Segurança DevOps 
- Proteção de cargas de trabalho de nuvem 
- Monitoramento da segurança integrada entre assinaturas 
- Componentes de monitoramento para coletar e armazenar dados 

O Defender para Nuvem é compatível com ambientes do Azure, AWS e Google Cloud. Os recursos básicos do GPSN são gratuitos, mas o Gerenciamento da Postura de Segurança na Nuvem e os planos de proteção de cargas de trabalho de nuvem têm custos adicionais








