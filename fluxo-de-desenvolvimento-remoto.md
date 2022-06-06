## 3. Fluxo de desenvolvimento remoto

### 3.1. Criar uma cópia do repositório localmente

```
git clone linkdorepositorio.git
```

### 3.2. Definir qual o endereço do repositório remoto receberá o código-fonte do repositório local

```
git remote origin linkdorepositorioremoto.git

```

### 3.3. Enviar o código-fonte do repositório local para o repositório remoto

```
git push -u origin main (Se for primeiro envio do código-fonte)
git push (Nos demais envios)
```

### 3.4. Verificar e baixar ajustes no código-fonte do repositório remoto para o repositório local

```
git pull
```
