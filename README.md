<h1 align="center">Resolver conflito</h1>

O primeiro passo consiste em identificar os arquivos que apresentam conflitos no Pull Request.

<img src="./assets/resolve.png" alt="imagem de ilustração" />

<br/>

Abra o Visual Studio Code e certifique-se de estar na branch que está enfrentando conflitos (no meu caso, é a branch FEAT/24).

<img src="./assets/resolve-1.png" alt="imagem de ilustração" />

<br/>

Crie uma nova branch que irá abordar a resolução desses conflitos.

Certifique-se de nomear essa branch da mesma forma que a branch conflituosa, adicionando apenas "fix".

Lembre-se sempre de criar a branch de resolução de conflitos com base na branch que está enfrentando conflitos.

Por exemplo, se a branch conflituosa é 'FEAT/24', a nova branch seria 'FEAT/24-fix'.

<img src="./assets/resolve-2.png" alt="imagem de ilustração" />

<br/>

Realize o pull da branch para a qual você está apontando na pull request para a sua própria branch.

<img src="./assets/resolve-3.png" alt="imagem de ilustração" />

<br/>

Resolva os conflitos e, após concluir a resolução, faça o push para a sua branch.

<img src="./assets/resolve-4.png" alt="imagem de ilustração" />

<br/>

Crie a Pull Request da branch que resolve o conflito (FEAT/24-fix), apontando para a branch que está enfrentando o conflito, no meu caso, 'FEAT/24'.

### Pull Request

FEAT/24 <- FEAT/24-fix

<img src="./assets/resolve-5.png" alt="imagem de ilustração" />

<br/>

Antes de efetuar o merge, revise os arquivos para garantir que tudo está correto.

Após essa verificação, proceda com o merge para a branch que está enfrentando conflitos.

<img src="./assets/resolve-6.png" alt="imagem de ilustração" />
<img src="./assets/resolve-7.png" alt="imagem de ilustração" />
<img src="./assets/resolve-8.png" alt="imagem de ilustração" />

<br/>

Sua branch está livre de conflitos.

<img src="./assets/resolve-9.png" alt="imagem de ilustração" />

<br/>

Para concluir, remova a branch criada para resolver o conflito.

<img src="./assets/resolve-10.png" alt="imagem de ilustração" />

<br/>
<p align="center">Desenvolvido por <a href="https://www.linkedin.com/in/rodrigo-de-jesus-silva/">Rodrigo Silva</a>
</p>
