#Apache Version 2.3/2.4

mod_proxy_fcgi

mod_proxy_scgi

mod_proxy_express

mod_remoteip

#Apache 2.1/2.2

Principais Melhorias

Authn/Authz
...
Caching
...
Proxying
O novo módulo mod_proxy_balancer fornece serviços de carregamento de balenceamento para mod_proxy. O novo módulo mod_proxy_ajp oferece suporte para o Protocolo Apache JServ versão 1.3, usado pelo Apache Tomcat.
Filtragem Inteligente (Smart Filtering)
O mod_filter introduz configuração dinâmica para o filtro de saída de dados. Permitindo que os filtros sejam condicionalmente inseridos, baseando-se nos cabeçalhos Request ou Response ou em variáveis do ambiente, ele acaba com os problemas de dependências e pedidos da arquitetura 2.0.
top
Melhorias nos Módulos

mod_authnz_ldap
Este módulo é uma migração do mod_auth_ldap, da versão 2.0 para a estrutura 2.2 de Authn/Authz. As novas funcionalidades incluem o uso de atributos LDAP e filtros de procura complexos na diretriz Require.
mod_info
Adicionado um novo argumento ?config que mostra a configuração das diretrizes analisadas pelo Apache, incluindo o nome do arquivo e o número da linha. Esse módulo também mostra a ordem de todos os ganchos de pedidos (request hooks) e informações adicionais sobre a compilação, similar ao comando httpd -V.
top

#NGINX version 1.12/1.13

The even‑numbered version (1.12) is our stable branch.
This branch is updated only when critical issues or security vulnerabilities need to be fixed.
For example, during the past year only three minor updates were made to the 1.10 stable branch.
The odd‑numbered version (1.13) is the mainline branch.
This branch is actively developed; new minor releases (1.13.1, 1.13.2, etc.) are made approximately every 4 to 6 weeks, regularly introducing new features and enhancements.

# WordPress version 4.8.1

wp-admin/css/themes.css
wp-admin/css/widgets.css
wp-admin/includes/class-wp-comments-list-table.php
wp-admin/includes/options.php
wp-admin/js/customize-controls.js
wp-admin/js/customize-nav-menus.js
wp-admin/js/widgets/media-widgets.js
wp-admin/js/widgets/text-widgets.js
wp-includes/class-oembed.php
wp-includes/class-wp-customize-widgets.php
wp-includes/class-wp-editor.php
wp-includes/class-wp-oembed-controller.php
wp-includes/default-widgets.php
wp-includes/js/media-views.js
wp-includes/js/media/views/uploader/inline.js
wp-includes/js/tinymce/plugins/wordpress/plugin.js
wp-includes/js/tinymce/skins/wordpress/wp-content.css
wp-includes/js/wp-api.js
wp-includes/media.php
wp-includes/rest-api.php
wp-includes/rest-api/class-wp-rest-server.php
wp-includes/script-loader.php
wp-includes/taxonomy.php
wp-includes/theme.php
wp-includes/version.php
wp-includes/widgets.php
wp-includes/widgets/class-wp-widget-media-video.php
wp-includes/widgets/class-wp-widget-media.php
wp-includes/widgets/class-wp-widget-text.php

# WordPress version 4.8
New Filter Hooks

file_mod_allowed replaces disallow_file_mods (#38673)
minimum_site_name_length (#39676)
nav_menu_submenu_css_class (#36163)
page_menu_link_attributes (#40359)
post_date_column_status (#39545)
signup_site_meta (#39223)
signup_user_meta (#39223)
wp_doing_cron (#39591)
widget_text_content (#40772)
rest_oembed_ttl (#40450)
widget_{$this->id_base}_instance (#32417)
Modified Filter Hooks

widget_text_content (#40772)
{$type}_template (#39525)
display_media_states (#39628)
media_library_show_audio_playlist (#31071)
media_library_show_video_playlist (#31071)
rest_pre_insert_comment (#39578)
wp_is_large_network (#40489)
