# defaultableSwap

The Valuation of Interest Rate Swap with Bilateral Counterparty Risk

ABSTRACT
This paper presents an analytical model for valuing interest rate swaps, subject to bilateral counterparty credit risk. The counterparty defaults are modeled by the reduced-form model as the first jump of a time-inhomogeneous Poisson process. All quantities modeled are market-observable. The closed-form solution gives us a better understanding of the impact of the credit asymmetry on swap value, credit value adjustment, swap rate and swap spread.

Conclusion
In this paper we present an analytical model for pricing defaultable IRS’s with asymmetric credit qualities. The model is based on the market models of interest rate dynamics and the reduced-form model of default time.
The object modeled under the market models is risk-observable. It is also consistent with the market standard approach for pricing caps/floors using Black’s formula. The market models have now become some of the most popular models for pricing such derivatives. They are generally considered to have more desirable theoretical calibration properties than short rate or instantaneous forward rate models.
	Unlike structural models, reduced-form models do not condition default explicitly on the value of the firm, and parameters related to the firm’s value need not be estimated to implement the model. For pricing and hedging, reduced-form models are the preferred methodology.
	Our closed-form solution shows that the value of a bilateral defaultable IRS is the sum of the values of individual bilateral defaultable swaplets. Each bilateral defaultable swaplet can be replicated by buying a risk-adjusted call option and selling a risk-adjusted put option. The risk-adjusting factors depend on hazard rates, recovery rates and settlement rules.
	In the case where the floating-rate payer is a LIBOR party, we confirm findings in Duffie and Huang (1996) that the swap spreads are relatively less sensitive to credit quality comparing to the bond spreads or the CDS spreads. The credit impact on swap rates is approximately linear. In the case where both parties have spreads against the LIBOR that was not studied closely before, we find that the credit impact on swap rates is not linear any more. The swap funding spreads have a significantly impact on swap spreads as well.

Reference
ArVanities, A., and Gregory, J., 2001, Credit: the complete guide to pricing, hedging and risk management, Risk Books.

Duffie, D. and Huang, M., 1996, Swap rates and credit quality, Journal of Finance, 51, 921-949.

Duffie, D. and Singleton, K.J., 1997, An econometric model of the term structure of interest rate swap yields, Journal of Finance, 52, 1287-1321

FinPricing, 2019, Data Analytics, https://finpricing.com/lib/IrSwap.html

Huge, B. and Lando, D., 1999, Swap pricing with two-sided default risk in a rating-based model, European Finance Review, 3, 239-268.

Hubner, G., 2001, The analytic pricing of asymmetric defaultable swaps, Journal of Banking & Finance, 25, 295-316

Jarrow, R. and Turnbull, S., 1995, Pricing options on financial securities subject to default risk, Journal of Finance, 50, 53-86.

Li, H., 1998, Pricing of swaps with default risk, Review of Derivatives Research, 2, 231-250.

Longstaff, F.A. and Schwartz, E.S., 1993, Valuing risky debt: a new approach, working paper, The Anderson Graduate School of Management, UCLA.

Rendleman, R.J., 1992, How risks are shared in interest rate swaps, Journal of Financial Services Research, 7, 5-34.

Sundarean, S., 1991, Valuation of swaps, in Recent Developments in International Banking and Finance, S. Khoury, ed. Amsterdam: North Holland.

Tang, Y. and Li, B., 2007, Quantitative analysis, derivatives modeling, and trading strategies, World Scientific Publishing.

Xiao, T., 2017, “A New Model for Pricing Collateralized OTC Derivatives.” Journal of Derivatives, 24(4), 8-20.

Xiao, T., 2015, “An Accurate Solution for Credit Valuation Adjustment (CVA) and Wrong Way Risk.” Journal of Fixed Income, 25(1), 84-95.
