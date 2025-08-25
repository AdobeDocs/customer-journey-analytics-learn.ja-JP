---
user-guide-title: Customer Journey Analytics
user-guide-url: /content/help/en/customer-journey-analytics-learn/tutorials/overview.html
type: Tutorial
source-git-commit: bdce32ca64fd14aeb760113b8df6ca96988069ce
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 79%

---


# Customer Journey Analytics チュートリアル {#tutorials}

+ [Customer Journey Analytics の概要](overview.md)
+ Customer Journey Analyticsの基本 {#cja-basics}
   + [Customer Journey Analytics とは](cja-basics/what-is-customer-journey-analytics.md)
   + [Customer Journey Analytics の概要](cja-basics/understanding-customer-journey-analytics.md)
   + [新しい用語と概念](cja-basics/new-terms-and-concepts-in-cja.md)
   + [Customer Journey Analytics のランディングページ](cja-basics/customer-journey-analytics-landing-page.md)
   + [AI アシスタントを使用](cja-basics/use-ai-assistant.md)
+ アーキテクチャ {#architecture}
   + [アーキテクチャと統合](architecture/architecture-and-integrations-of-cja.md)
+ データの準備と計画 {#data-prep}
   + [データの操作](data-prep/working-with-data-in-cja.md)
   + [Adobe Analytics データの取り込み、マッピング、変換](data-prep/ingest-map-and-transform-adobe-analytics-data.md)
   + [Adobe Analytics 分類データの取り込みと使用](data-prep/ingest-and-use-analytics-classifications.md)
+ アクセス制御 {#access-control}
   + [権限の設定](permissions/set-up-permissions.md)
+ 接続 {#connections}
   + [Experience Platform データソースへの接続](connections/connecting-customer-journey-analytics-to-data-sources-in-platform.md)
   + [接続設定の表示、トラブルシューティング、変更](connections/connections-details-experience-in-cja.md)
   + [接続への新しいデータの追加](connections/add-past-data-to-an-existing-connection-in-cja.md)
   + [ルックアップデータおよびプロファイルデータの CJA ルックアップ](connections/cja-lookup-data.md)
+ 訪問者の識別 {#visitor-id}
   + [CJA での ID の使用方法について](visitor-id/understanding-how-customer-journey-analytics-uses-identity.md)
   + [欠落しているユーザー ID の設定](visitor-id/configure-missing-person-id.md)
   + [ステッチの概要](visitor-id/overview-of-stitching.md)
   + [グラフベースのステッチの概要](visitor-id/graph-based-stitching-overview.md)
+ データビュー {#data-views}
   + [CJA のデータビュー設定の概要](data-views/overview-of-configuring-data-views-for-cja.md)
   + [データビューの基本設定](data-views/basic-configuration-for-data-views.md)
   + [データビューのコンポーネント設定](data-views/configuring-component-settings-in-data-views.md)
   + [データビューのコンポーネントタイプ設定](data-views/component-type-settings-in-data-views.md)
   + [概要レベルのデータソースの作成](data-views/create-summary-level-data-sources.md)
   + [データビューの指標の書式設定](data-views/formatting-metrics-in-data-views.md)
   + [サブ文字列コンポーネントの設定](data-views/configure-substring-component-settings.md)
   + [データビューでの指標値の包含または除外](data-views/include-or-exclude-metric-values-in-data-views.md)
   + [データビューでの分析用の値バケットの作成](data-views/creating-value-buckets-in-data-views-for-analysis.md)
   + [データビューでのディメンション値の包含または除外](data-views/include-or-exclude-dimension-values-in-data-views.md)
   + [データビューでのバインディングディメンション](data-views/binding-dimensions-in-data-views.md)
   + [データビューでの値なしオプションの設定](data-views/configure-no-value-options-in-data-views.md)
   + [データビューでのアトリビューション設定](data-views/attribution-settings-in-data-views.md)
   + [通貨換算](data-views/currency-conversion.md)
   + 派生フィールド{#derived-fields}
      + [派生フィールドの作成](data-views/derived-fields/derived-fields-in-cja.md)
      + [数学関数の使用](data-views/derived-fields/use-the-math-function-in-derived-fields.md)
      + [Next 関数または Previous 関数の使用](data-views/derived-fields/use-the-next-previous-function-in-derived-fields.md)
      + [イベントの深度をカスタマイズ](data-views/derived-fields/customize-event-depth-in-derived-fields.md)
      + [型キャストを使用](data-views/derived-fields/use-typecasting-in-derived-fields.md)
      + [イベント間の時間を計算するには、日付計算を使用します](data-views/derived-fields/use-date-math-to-calculate-time-between-events.md)
+ Data Insights エージェント {#data-insights-agent}
   + [はじめに](data-insights-agent/introduction-to-the-data-insights-agent.md)
   + [ユースケース](data-insights-agent/data-insights-agent-use-cases.md)
   + [Data Insights Agentの使用](data-insights-agent/use-the-data-insights-agent.md)
+ Analysis Workspace {#analysis-workspace}
   + ワークスペースプロジェクト {#workspace-projects}
      + [Analysis Workspace の概要](analysis-workspace/workspace-projects/analysis-workspace-overview.md)
      + [新規プロジェクトの作成](analysis-workspace/workspace-projects/build-a-new-project.md)
      + [Analysis Workspace テンプレート](analysis-workspace/workspace-projects/analysis-workspace-templates.md)
      + [Workspaceコメント](analysis-workspace/workspace-projects/workspace-commenting.md)
      + ジャーニー分析 {#journey-analysis}
         + [ジャーニーキャンバスビジュアライゼーション](analysis-workspace/workspace-projects/journey-analysis/journey-canvas-viz.md)
   + パネル {#panels}
      + [フリーフォームパネルへのコンポーネントの追加](analysis-workspace/panels/add-components-to-the-freeform-panel.md)
      + [アトリビューションパネルの作成](analysis-workspace/panels/build-the-attribution-panel.md)
      + [次または前の項目パネルの設定](analysis-workspace/panels/configure-next-previous-item-panel.md)
      + [実験パネルの使用](analysis-workspace/panels/use-the-experimentation-panel.md)
      + [クイックインサイトパネルの使用](analysis-workspace/panels/use-the-quick-insights-panel.md)
   + テンプレート {#templates}
      + [テンプレートの使用](analysis-workspace/templates/use-templates.md)
      + [カスタムテンプレートの作成](analysis-workspace/templates/create-custom-templates.md)
   + ビジュアライゼーション {#visualizations}
      + [クロスチャネルビジュアライゼーションの作成](analysis-workspace/visualizations/creating-cross-channel-visualizations-in-customer-journey-analytics.md)
      + [クロスチャネルアトリビューション](analysis-workspace/visualizations/cross-channel-attribution-in-customer-journey-analytics.md)
      + [インテリジェントキャプションの作成](analysis-workspace/visualizations/intelligent-captions.md)
      + [面グラフのビジュアライゼーションの追加](analysis-workspace/visualizations/add-area-visualizations.md)
      + [棒グラフのビジュアライゼーションを追加](analysis-workspace/visualizations/add-bar-visualizations.md)
      + [ブレットグラフのビジュアライゼーションの追加](analysis-workspace/visualizations/add-bullet-graph-visualizations.md)
      + [ドーナツグラフのビジュアライゼーションの追加](analysis-workspace/visualizations/add-donut-visualizations.md)
      + [線グラフのビジュアライゼーションの追加](analysis-workspace/visualizations/add-line-visualizations.md)
      + [マップビジュアライゼーションの設定と使用](analysis-workspace/visualizations/configure-and-use-the-map-visualization.md)
      + [概要のビジュアライゼーションの使用](analysis-workspace/visualizations/use-summary-visualizations.md)
      + [テキストのビジュアライゼーションの追加](analysis-workspace/visualizations/add-text-visualizations.md)
      + [散布図のビジュアライゼーションの使用](analysis-workspace/visualizations/use-scatterplot-visualizations.md)
      + [ツリーマップのビジュアライゼーションの追加](analysis-workspace/visualizations/add-treemap-visualizations.md)
      + [完全な積み重ねグラフのビジュアライゼーションの作成](analysis-workspace/visualizations/create-stacked-visualizations.md)
      + [ビジュアライゼーションへの予測の追加](analysis-workspace/visualizations/forecasting.md)
   + 注釈 {#annotations}
      + [注釈を作成](analysis-workspace/annotations/create-an-annotation.md)
   + キュレーションと共有 {#curate-and-share}
      + [Analysis Workspace で誰とでも共有](analysis-workspace/curate-and-share/share-with-anyone-in-analysis-workspace.md)
   + ヒントとテクニック {#tips-and-tricks}
      + [動的ドロップダウンセグメントの作成](analysis-workspace/tips-and-tricks/dynamic-drop-downs.md)
+ Adobe Product Analytics {#adobe-product-analytics}
   + [Adobe Product Analytics の概要](adobe-product-analytics/adobe-product-analytics-overview.md)
+ ガイド付き分析 {#guided-analysis}
   + [Workspaceでのガイド付き分析の使用](guided-analysis/guided-analysis-in-workspace.md)
   + [アクティブな増加](guided-analysis/active-growth.md)
   + [コンバージョントレンド](guided-analysis/conversion-trends.md)
   + [エンゲージメント](guided-analysis/engagement.md)
   + [初回使用の影響](guided-analysis/first-use-impact.md)
   + [頻度](guided-analysis/frequency.md)
   + [ファネル](guided-analysis/funnel.md)
   + [純増加率](guided-analysis/net-growth.md)
   + [リリースの影響](guided-analysis/release-impact.md)
   + [リテンション](guided-analysis/retention.md)
   + [Timeline](guided-analysis/timeline.md)
   + [トレンド](guided-analysis/trends.md)
+ コンポーネント {#components}
   + セグメント {#filters}
      + [セグメント：概要](components/filters/introduction-to-filters-in-cja.md)
      + [クイックセグメントの作成](components/filters/create-a-quick-filter.md)
      + [クロスチャネルセグメントの作成](components/filters/creating-cross-channel-filters-in-customer-journey-analytics.md)
      + [ディメンションとしてのセグメントの使用](components/filters/use-filters-as-dimensions.md)
      + [セグメントからのオーディエンスの作成](components/filters/create-audiences-from-segments.md)
      + [Adobe Analytics セグメントの Customer Journey Analytics への移行](components/filters/moving-adobe-analytics-segments-to-customer-journey-analytics.md)
   + ディメンション {#dimensions}
      + [イベント深度](components/dimensions/event-depth-in-cja.md)
   + 計算指標 {#calc-metrics}
      + [Customer Journey Analytics における計算指標の概要](components/calc-metrics/introduction-to-calculated-metrics-in-customer-journey-analytics.md)
      + [Adobe Analytics から Customer Journey Analytics への計算指標の移行](components/calc-metrics/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.md)
   + オーディエンス {#audiences}
      + [オーディエンスパブリッシング](components/audiences/audience-publishing-for-cja.md)
   + データ辞書 {#data-dictionary}
      + [データ辞書の使用](components/data-dictionary/use-data-dictionary.md)
+ コンテンツ分析 {#content-analytics}
   + [はじめに](content-analytics/introduction-to-content-analytics.md)
   + [仕組み](content-analytics/how-it-works.md)
   + [設定を作成](content-analytics/create-configuration.md)
   + [設定を編集](content-analytics/edit-configuration.md)
+ ダッシュボード（スコアカード） {#dashboards}
   + [モバイルスコアカードの作成](dashboards/create-a-mobile-scorecard.md)
   + [モバイルスコアカードへのアクセスでのエグゼクティブの支援](dashboards/assist-executives-to-access-mobile-scorecards.md)
+ エクスポート {#exporting}
   + [完全なテーブルの書き出し](exporting/full-table-export.md)
   + Report Builder {#report-builder}
      + [Customer Journey Analytics 用の Report Builder](exporting/report-builder/report-builder-for-customer-journey-analytics.md)
      + [Report Builder を使用した Customer Journey Analytics ワークブックのスケジューリング](exporting/report-builder/schedule-cja-workbooks-using-report-builder.md)
+ レポートアクティビティマネージャー {#reporting-activity-manager}
   + [レポートアクティビティマネージャーの使用](reporting-activity-manager/use-the-reporting-activity-manager.md)
+ Experience Platformの統合 {#experience-platform-integration}
   + [Adobe Journey Optimizerのレポート機能の強化](experience-platform-integration/enhanced-reporting-for-adobe-journey-optimizer.md)
+ ユースケース {#use-cases}
   + データビューのユースケース {#data-views-use-cases}
      + [初回のセッションとリピートセッションのレポート](use-cases/data-views-use-cases/first-time-and-returning-sessions.md)
      + [日付フィールドのサポートの使用](use-cases/data-views-use-cases/leverage-date-field-support.md)
   + 複雑なデータ {#complex-data}
      + [オブジェクトの配列を使用](use-cases/complex-data/object-arrays-in-cja.md)
+ ブループリント {#blueprints}
   + [Customer Journey Analytics ブループリント](https://experienceleague.adobe.com/ja/docs/blueprints-learn/architecture/customer-journey-analytics/overview){target=_blank}
   + [デジタル行動データ統合のシナリオ](https://experienceleague.adobe.com/ja/docs/analytics-platform/using/cja-usecases/cross-channel/cross-channel){target=_blank}
   + [着信転送ジャーニー分析シナリオ](https://experienceleague.adobe.com/ja/docs/analytics-platform/using/cja-usecases/cross-channel/call-center){target=_blank}
