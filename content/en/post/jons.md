---
title: "Theory Seminar: Jon Schneider"
date: 2023-09-01
---

The theory seminar will restart this week with a talk by Jon Schneider of Google Research. The talk will take place at Room 401B, 3401 Walnut Street from 12-1 PM on Friday.

**Title:** U-Calibration: Forecasting for an Unknown Agent

**Abstract:** We will discuss the problem of evaluating forecasts of binary events whose predictions are consumed by rational agents who take an action in response to a prediction, but whose utilities are unknown to the forecaster. We will argue that two common classes of metrics for evaluating forecasts -- scoring rules (e.g. the Brier score) and calibration -- are in some sense inadequate, neither tightly characterizing when an unknown agent can trust the forecaster.

Motivated by this, we present a new efficiently-computable metric for evaluating forecasts that we call U-calibration, equal to the maximal regret of the sequence of forecasts when evaluated under any bounded scoring rule. We will show that sublinear U-calibration error is a necessary and sufficient condition for all agents to achieve sublinear regret guarantees. We will also demonstrate an online algorithm that achieves O(sqrt(T)) U-calibration error (on par with optimal rates for optimizing for a single scoring rule, and bypassing lower bounds for the traditionally calibrated learning procedures).  Finally, we will discuss generalizations of U-calibration to the multiclass prediction setting and its connections to swap regret and strategizing in games.

Based on work with Robert Kleinberg, Renato Paes Leme, and Yifeng Teng.
