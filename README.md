# BianDeloitte

_id: a unique identifier for the billing record.

customer_id: a unique identifier for the customer who is being billed.

type: the type of billing record, which in this case is "m_bill".

insert_ts: a timestamp indicating when the billing record was inserted.

date: the date of the billing period covered by the record.
eff_date: the effective date of the billing period covered by the record.
bw: the amount of bandwidth used by the customer during the billing period.

calc_cost: an object containing details about the calculated cost of the billing record, 
including subtotal, total, and breakdowns of the costs associated with different services or time periods.

cname: the name of the company or entity that calculated the cost.

cid: the unique identifier of the customer being billed.
period: an object representing the billing period covered by the record, with fields from and to.
subtotal: the subtotal cost for the billing period.
vat: the value-added tax applied to the billing period, if any.
vat_rates: an object containing details about the VAT rates applied to different services or time periods.
total: the total cost for the billing period.

explain: an object containing a breakdown of the costs associated with different services or time periods,
as well as any discounts or other factors that may have affected the cost.

gusage: an object representing the cost associated with the customer's usage of different services or products.
sum: the total cost associated with the customer's usage.
breakdown: an array of objects representing the cost associated with specific services or products, if any.
precommit: an object representing the cost associated with any pre-commitments or guarantees made by the customer.
sum: the total cost associated with pre-commitments or guarantees.

breakdown: an array of objects representing the cost associated with specific pre-commitments or guarantees,
if any. Each object contains fields from and to indicating the time period covered, as well as the cost, precommitment amount, and other factors affecting the cost.
