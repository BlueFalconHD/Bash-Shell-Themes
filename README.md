## Bash Shell Themes
### By BlueFalconHD










# Themes:

- Vintage Dark:

  ![alt text](https://github.com/BlueFalconHD/Bash-Shell-Themes/blob/main/Screenshot%202021-04-25%20162754.png "Hi")
  
  How to make:
  
  set the contents of `~/.bash_profile` to:
  ```
  blue="\033[1;34m"
  none="\033[1;00m"
  yellow="\033[1;33m"
  yellowb="\033[7;33m"
  green="\033[4;32m"
  purple="\033[6;35m"
  n="\033[0;00m"
  echo -e "                                                  $blue -------------------$n
  $blue                 &@                               $none  $HOSTNAME$n
  $blue               %&&&              %&&,             $blue -------------------$n
  $blue               .&&&@         &&@@&&,              $green Bash Version:$n
  $blue             &@ &@@&      &&&&&&@@#               $yellow $BASH_VERSION$n
  $blue            &&&&.&&&@   &&&&&&&&&@                $green User:$n
  $blue            @&&&@&&&&  *&&@@&@&&&                 $yellow $USER$n
  $blue          %@ .&&&&&&@&  &&&@&&&&%                 $green Color Support:$n
  $blue          &&&&,@&&&&&&@ /&&&&&&&                  $yellow $TERM$n
  $blue           @&&@&&&&@&&&/ &&&&&&&                  $green Home Directory:$n
  $blue          @(  &@&&&&&&&& .@&&&&*                  $yellow $HOME$n
  $blue          @@@&&@&&&&&&&&& @&&&&                   $green Distro:$n
  $blue            &&&&&&&&&&&&&@.&&&&                   $yellow $WSL_DISTRO_NAME $n
  $blue           &@  &&&&&&&&&&&&%&&@                   $blue-------------------$n
  $blue            &&&&&&&&&&&&&&&&&&&                   $green Alternate Directory (for host such as WINDOWS): $n
  $blue              @&&&&&&&@&&@&&&&&                   $yellow $PWD
  $blue              @@@(,.@&&&&&&&&&&.                  $green History File: $n
  $blue               &&&&&&&&&@&&&&&@@&&&&&&@           $yellow $HISTFILE $n
  $blue              @&&&&&&@&&&&&&&&&&&&&&&&&&&&&&      $green Host Architecture: $n
  $blue          @&&&&&&&@&&&&&&&&&&&&&&&&&&&&&&&& &&    $yellow $HOSTTYPE $n
  $blue      @&&&&&&&&&&&&&&&&&&&&&&&&&*         .@&&&   $green Shell DIR: $n
  $blue  @&&&&&@*&&&&&&&&@&&/  @&@&&&&&&                 $yellow $SHELL $n
  $blue       &&&@%&&&&&@@       &&&&&@&                 $green Encoding Language: $n
  $blue         .&&& &&&            &&&&& @&&&*          $yellow $LANG $n
  $blue              #@               %&&&&&& @          $green Text Editor: $n
  $blue                                &&   ,            $yellow Vim $n
  
  $purple ███████████ ████                 ███████████ ███            █████
  ░░███░░░░░██░░███                ░░███░░░░░██░░░            ░░███
   ░███    ░███░████████ ████ ██████░███    ░██████████████ ███████
   ░██████████ ░██░░███ ░███ ███░░██░█████████░░██░░███░░█████░░███
   ░███░░░░░███░███░███ ░███░███████░███░░░░░██░███░███ ░░░███ ░███
   ░███    ░███░███░███ ░███░███░░░ ░███    ░██░███░███   ░███ ░███
   ███████████ ████░░███████░░██████████████████████████  ░░████████  
  ░░░░░░░░░░░ ░░░░░ ░░░░░░░░ ░░░░░░░░░░░░░░░░░░░░░░░░░░    ░░░░░░░░ $n

            $yellowb D    E    V    E    L    O    P    E    R $n
  "
  
  
  u="$USER"
  DEFAULT=$PS1
  PS1="\[\033[1;31m\]Date : {\d \@} \[\033[1;33m\]User : {\u} \[\033[4;34m\]DIR : {\w}\[\033[00m\] \[\033[1;37m\] \$  \[\033[1;32m\]=> \[\033[1;36m\]"
  cd ~
  ```
  
  
  You can change the big block of text that looks like "BlueBird" to whatever you want. You Can also change the stuff below that.
  
  
  #### Font:
  
  if you have the option to change a font, I reccomend `SF Mono Semi-Bold`
  
  ![alt text](https://github.com/BlueFalconHD/Bash-Shell-Themes/blob/main/Screenshot%202021-04-25%20165421.png "Hi")
