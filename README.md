bash

cd /home/claude/ccs_full
find app jobs alembic -type f -name "*.py" | sort
Output

alembic/env.py
alembic/versions/287d370eafcb_initial_schema.py
alembic/versions/a1b2c3d4e5f6_catalog_extension.py
alembic/versions/b2c3d4e5f6a7_sale_item_variant.py
app/__init__.py
app/core/__init__.py
app/core/config.py
app/core/deps.py
app/core/errors.py
app/core/pagination.py
app/core/security.py
app/db/__init__.py
app/db/base.py
app/db/seed.py
app/events/__init__.py
app/events/dispatcher.py
app/main.py
app/models/__init__.py
app/routers/__init__.py
app/routers/account.py
app/routers/admin.py
app/routers/auth.py
app/routers/categories.py
app/routers/customers.py
app/routers/dashboard.py
app/routers/installments.py
app/routers/ledger.py
app/routers/notifications.py
app/routers/payments.py
app/routers/products.py
app/routers/sales.py
app/schemas.py
app/services/__init__.py
app/services/event_service.py
app/services/image_service.py
app/services/ledger_service.py
app/services/payment_service.py
app/services/sale_service.py
app/services/sequence_service.py
jobs/__init__.py
jobs/overdue_job.py
