# 財務分析儀表板 Financial Analysis Dashboard

本專案涉及使用 Microsoft Power BI 開發動態、自動化的財務儀表板。此儀表板旨在取代耗時、重複的每日Excel報表產生任務，為關鍵財務績效指標和度量提供即時洞察。

This project involves the development of a dynamic, automated financial dashboard using Microsoft Power BI. The dashboard is designed to replace the time-consuming, repetitive task of generating daily Excel reports, providing real-time insights into key financial performance indicators (KPIs) and metrics.


<img width="1522" height="872" alt="image" src="https://github.com/user-attachments/assets/85f7a3ea-9eb6-4d79-8bf6-7f1a2a4110aa" />

# 核心組件與架構 Key Components & Architecture

**1. 集中化資料來源：SQL 資料倉儲**

一個專用的 SQL 資料倉儲作為所有財務資料的單一權威來源。它整合了來自交易系統（如ERP、CRM）的數據，確保報告的一致性、可靠性和可擴展性。

**2. 自動化資料管道與刷新**

Power BI 直接連線到 SQL 資料倉儲。
配置了每日定時刷新。此過程會自動從倉庫提取最新資料到 Power BI 資料集中，確保儀表板無需人工幹預即可反映當日資訊。

**3. 互動式財務儀表板**

Power BI 報表包含一套全面的視覺化元件，包括：關鍵績效指標卡： 用於顯示如收入、利潤率、支出等高層級指標。

趨勢分析圖表： 顯示隨時間（每日、每月、每季）的績效表現。

下鑽報告： 允許使用者探索匯總資料背後的細節（例如，按部門、產品線或地區）。

直覺的設計使利害關係人能夠即時評估財務健康狀況並識別趨勢。


**1. Centralized Data Source: SQL Data Warehouse**

A dedicated SQL Data Warehouse​ serves as the single, authoritative source for all financial data.
It consolidates data from transactional systems (ERP, CRM), ensuring consistency, reliability, and scalability for reporting.

**2. Automated Data Pipeline & Refresh**

Power BI connects directly to the SQL Data Warehouse.
A scheduled refresh​ is configured to run daily. This process automatically pulls the latest data from the warehouse into the Power BI dataset, ensuring the dashboard reflects the current day's information without any manual intervention.

**3. Interactive Financial Dashboard**

The Power BI report features a comprehensive set of visualizations, including: Key Performance Indicator (KPI) Cards:​ For high-level metrics like Revenue, Profit Margin, and Expenses.

Trend Analysis Charts:​ Showing performance over time (Daily, Monthly, Quarterly).

Drill-Down Reports:​ Allowing users to explore details behind summary figures (e.g., by department, product line, or region).

The intuitive design enables stakeholders to instantly assess financial health and identify trends.

# 核心效益與成果 Core Benefits & Outcome

**消除手動報告**： 完全取消了每日產生Excel報表的需求，節省了大量分析師的時間。

**即時、可信賴的洞察**： 基於集中化的 SQL 資料倉儲，為利害關係人提供準確、最新的財務資料存取。

**增強決策能力**： 使管理階層能夠立即掌握績效動態，支援更快、更明智的業務決策。

**可擴展的基礎**： SQL 資料倉儲的使用確保了該解決方案能夠應對不斷增長的資料量和不斷變化的報告需求。

**Eliminated Manual Reporting:​** Completely removed the need for daily Excel report generation, saving significant analyst time.

**Real-Time, Trusted Insights:​** Provides stakeholders with access to accurate, up-to-date financial data based on the centralized SQL Data Warehouse.

**Enhanced Decision-Making:​** Empowers management with immediate visibility into performance, supporting faster and more informed business decisions.

**Scalable Foundation:​** The use of SQL Data Warehouse ensures the solution can handle growing data volumes and evolving reporting needs.
