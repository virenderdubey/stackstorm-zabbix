# Change Log

## 0.1.3

- Added a new action `test_credentials` that tests if the credentials in the config are valid.
  Contributed by Nick Maludy (Encore Technologies)

## 0.1.2

- Added base action class with common code. Removed duplicate code from other actions
- Added host_get_id action action to return the id of a Zabbix Host
- Added host_update_status action to change the status of a Zabbix Host
- Added host_delete action to delete a Zabbix Host
- Added maintenance_create_or_update action to create a maintenance window or update one if it already exists
- Added maintenance_delete action to delete a maintenance window

Contributed by Brad Bishop (Encore Technologies)

## 0.1.1

- Set a secret option to the password property in the config.schema.yaml

## 0.1.0

- Initial release
