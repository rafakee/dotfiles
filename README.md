
# Dotfiles

<div  align="center">

<img  src="https://raw.githubusercontent.com/rafakee/dotfiles/refs/heads/master/screenshot.png"  alt="preview"  width="800px"/>

</div>


## Sobre

Estou disponibilizando essa coleção de dotfiles para proporcionar um visual Cyberpunk e moderno ao ambiente desktop no arch linux


## Paleta

- ![#c5003c](https://placehold.co/15x15/c5003c/c5003c.png) `#c5003c`
- ![#180007](https://placehold.co/15x15/180007/180007.png) `#180007`


**Environment:**

- Arch Linux

- Hyprland

- Hyprpaper

- Kitty

- Yazi

- VS Code

- Waybar


## Requisitos

- Linux (Arch)

- Git

- [GNU Stow](https://www.gnu.org/software/stow/) para gerenciar links simbólicos

- [Fira Code](https://archlinux.org/packages/extra/any/ttf-fira-code/) para exibição de textos no Kitty e no Waybar

## Instalação

1 - Clone este repositório:

```bash

git  clone  https://github.com/rafakee/dotfiles

```

2 - Entre na pasta:

```bash

cd  dotfiles

```

3 - Execute os comandos que desejar para aplicar as configuracoes correspondentes através da criação de links simbólicos:

```bash
stow  hyprland  # Para configur o Hyprland
stow  waybar  # Para configur o Waybar
stow  kitty  # Para configur o Kitty
stow  rofi  # Para configur o Rofi
```


## Dependências

| Hyprland  | sudo pacman -S hyprland  
|-----------|--------------------------|
| Hyprpaper | sudo pacman -S hyprpaper |
| Waybar    | sudo pacman -S waybar    |
| Kitty     | sudo pacman -S kitty     |
| Rofi      | sudo pacman -S rofi      |
| Hyprshot  | sudo pacman -S hyprshot  |
| Yazi      | sudo pacman -S yazi      |


## Atalhos Adicionais

`Super + f` -> Full Screen

`Super + PrtScn` -> Captura de tela 

`Super + Shift + P` -> Captura regiao da tela 


## Licença

  

Este projeto está licenciado sob a [MIT License](LICENSE).

---
Feito com ❤ por @rafakee
---

Obrigado por ter lido até aqui! Toma um cookie 🍪

<div  align="center">
  <h2>
	  I use Arch btw
  </h2>
</div>
