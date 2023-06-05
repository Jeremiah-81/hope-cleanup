# hope-cleanup





.panel-body > p:last-child { margin-bottom: 0; }

.big-currency {
	font-weight: lighter;

	.symbol { font-size: 40px; }
	.amount { font-size: 48px; margin-left: -4px; }
	.cents { font-size: 24px; margin-left: -4px; position: relative; top: -12px; }
}

.big-date {
	font-size: 48px;
}

.account-item
{
	height: 330px;

	.body {
		height: 100%;
	}

	.account-item-footer {
		position: absolute;
		bottom: 15px;
	}
}

.pl-24 { padding-left: 24px; }

@media (min-width: 1200px)
{
	.full-image-container:before
	{
		width: 100% !important;
		height: 100%;
		right: 0 !important;
		top: 0;
		background-color: rgba(55, 55, 55, 0.5) !important;
	}
}

.slideshow .dark-translucent-bg {
	background-color: rgba(0, 0, 0, 0.15) !important;
}

.main-navigation .badge {
    position: absolute;
    top: 17px;
    right: 4px;
    font-size: 12px;
    color: inherit;
    font-weight: 300;
    text-transform: uppercase;
    background-color: #777;
    padding: 2px 4px;
    color: white;
    min-width: 16px;
    font-weight: 400;
}