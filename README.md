![valid XHTML][checkmark]
[checkmark]: https://raw.githubusercontent.com/mozgbrasil/mozgbrasil.github.io/master/assets/images/logos/Red_star_32_32.png "MOZG"
[psr4]: http://www.php-fig.org/psr/psr-4/
[requerimentos]: http://mozgbrasil.github.io/requerimentos/
[getcomposer]: https://getcomposer.org/
[uninstall-mods]: https://getcomposer.org/doc/03-cli.md#remove

# Mozg\Fee

## Sinopse

Módulo de juros aos métodos de pagamentos

## Instalação - Atualização - Desinstalação - Desativação

Esta biblioteca destina-se a ser instalado usando o [Composer][getcomposer].

Autoloading compatível é [PSR-4][psr4]

--

Para qualquer atualização no Magento sempre mantenha o Compiler e o Cache desativado

--

### Para instalar o módulo execute o comando a seguir no terminal do seu servidor

    composer require mozgbrasil/magento-fee-php55:dev-master

-- 

### Para atualizar o módulo execute o comando a seguir no terminal do seu servidor

	composer clear-cache && composer update

Na ocorrência de erro, renomeie a pasta /vendor/mozgbrasil e execute novamente

Para checar a data do módulo execute o seguinte comando

	grep -ri 'time": "' ./vendor/mozgbrasil

--

### Para [desinstalar][uninstall-mods] o módulo execute o comando a seguir no terminal do seu servidor

    composer remove mozgbrasil/magento-fee-php55 && composer clear-cache && composer update

--

### Para desativar o módulo

Renomeie a pasta do módulo

Cada módulo tem a sua pasta no diretório /vendor/mozgbrasil/

## Badges

[![Join the chat at https://gitter.im/mozgbrasil](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mozgbrasil/)
[![Latest Stable Version](https://poser.pugx.org/mozgbrasil/magento-fee-php55/v/stable)](https://packagist.org/packages/mozgbrasil/magento-fee-php55)
[![Total Downloads](https://poser.pugx.org/mozgbrasil/magento-fee-php55/downloads)](https://packagist.org/packages/mozgbrasil/magento-fee-php55)
[![Latest Unstable Version](https://poser.pugx.org/mozgbrasil/magento-fee-php55/v/unstable)](https://packagist.org/packages/mozgbrasil/magento-fee-php55)
[![License](https://poser.pugx.org/mozgbrasil/magento-fee-php55/license)](https://packagist.org/packages/mozgbrasil/magento-fee-php55)
[![Monthly Downloads](https://poser.pugx.org/mozgbrasil/magento-fee-php55/d/monthly)](https://packagist.org/packages/mozgbrasil/magento-fee-php55)
[![Daily Downloads](https://poser.pugx.org/mozgbrasil/magento-fee-php55/d/daily)](https://packagist.org/packages/mozgbrasil/magento-fee-php55)
[![Build Status](https://travis-ci.org/mozgbrasil/magento-fee-php55.svg?branch=master)](https://travis-ci.org/mozgbrasil/magento-fee-php55)
[![Reference Status](https://www.versioneye.com/php/mozgbrasil:magento-fee-php55/reference_badge.svg?style=flat-square)](https://www.versioneye.com/php/mozgbrasil:magento-fee-php55/references)
[![Dependency Status](https://www.versioneye.com/php/mozgbrasil:magento-fee-php55/1.0.0/badge?style=flat-square)](https://www.versioneye.com/php/mozgbrasil:magento-fee-php55/1.0.0)

:cat2: