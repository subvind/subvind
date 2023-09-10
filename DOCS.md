git submodule update --init --recursive --remote
git submodule add git@github.com:subvind/copyright.git

git submodule deinit -f ./TenantERP
git rm --cached ./TenantERP
