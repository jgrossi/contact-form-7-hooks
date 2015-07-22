# Contact Form 7 Hooks

Here you can find some [Contact Form 7](https://wordpress.org/plugins/contact-form-7/) actions and filters (hooks) available for use. The last used version is 4.2.1.

## Filters

- `wpcf7_contact_form_default_pack`

```php
/**
 * Description
 *
 * @param $contact_form
 * @param $args
 * @return $contact_form
 */
add_filter('wpcf7_contact_form_default_pack', function($contact_form, $args) {
    return $contact_form;
});
```

- `wpcf7_contact_form_properties`

```php
/**
 * Description
 *
 * @param $properties
 * @param $cf7
 * @return $properties
 */
add_filter('wpcf7_contact_form_properties', function($properties, $cf7) {
    return $properties;
});
```

- `wpcf7_form_action_url`

```php
/**
 * Used to change the form action URL
 *
 * @param $url the current URL
 * @return string The new URL you want
 */
add_filter('wpcf7_form_action_url', function($url) {
    return $url;
});
```

- `wpcf7_form_id_attr`

```php
/**
 * Change de form HTML id value
 *
 * @param $html_id The current id value
 * @return string The new id
 */
add_filter('wpcf7_form_id_attr', function($html_id) {
    return $html_id;
});
```

- `wpcf7_form_name_attr`

```php
/**
 * Change de form HTML name
 *
 * @param $html_name The actual name
 * @return string The new name
 */
add_filter('wpcf7_form_name_attr', function($html_name) {
    return $html_name;
});
```

- `wpcf7_form_class_attr`

```php
/**
 * Change de form class name
 *
 * @param $html_class The actual class name
 * @return string The new class name
 */
add_filter('wpcf7_form_class_attr', function($html_class) {
    return $html_class;
});
```



