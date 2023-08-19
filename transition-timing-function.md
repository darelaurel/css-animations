
transition: property duration timing-function delay|initial|inherit;

**ease**
Correspond à cubic-bezier(0.25, 0.1, 0.25, 1.0) : c'est la valeur par défaut, la vitesse de la transition augmente au milieu de celle-ci puis ralentit à la fin.

**linear**
Correspond à cubic-bezier(0.0, 0.0, 1.0, 1.0) : la transition s'effectue à vitesse constante.

**ease-in**
Correspond à cubic-bezier(0.42, 0, 1.0, 1.0) : la transition commence doucement puis la vitesse augmente jusqu'à ce qu'elle soit terminée.

**ease-out**
Correspond à cubic-bezier(0, 0, 0.58, 1.0) : la transition commence rapidement puis ralentit jusqu'à la fin.

**ease-in-out**
Correspond à cubic-bezier(0.42, 0, 0.58, 1.0) : la transition commence lentement, accèlere puis ralentit à nouveau avant la fin.

**steps(int,start|end)**	

Specifies a stepping function, with two parameters. The first parameter specifies the number of intervals in the function. It must be a positive integer (greater than 0). The second parameter, which is optional, is either the value "start" or "end", and specifies the point at which the change of values occur within the interval. If the second parameter is omitted, it is given the value "end"

