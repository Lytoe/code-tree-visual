# Project Code Tree\n\n<details><summary>📂 **check-invalid-imports.js** (51 lines - 0.4%)</summary>

  <details><summary>📂 **check-invalid-imports.js** (51 lines - 0.4%)</summary>

    - check-invalid-imports.js (51 lines - 0.4%)

</details>

</details>
<details><summary>📂 **lint-colors.js** (38 lines - 0.3%)</summary>

  <details><summary>📂 **lint-colors.js** (38 lines - 0.3%)</summary>

    - lint-colors.js (38 lines - 0.3%)

</details>

</details>
<details><summary>📂 **next-env.d.ts** (5 lines - 0%)</summary>

  <details><summary>📂 **next-env.d.ts** (5 lines - 0%)</summary>

    - next-env.d.ts (5 lines - 0%)

</details>

</details>
<details><summary>📂 **src** (14173 lines - 98.6%)</summary>

  <details><summary>📂 **features** (9754 lines - 67.8%)</summary>

    <details><summary>📂 **classifier** (38 lines - 0.3%)</summary>

      <details><summary>📂 **hooks** (38 lines - 0.3%)</summary>

        - useClassifier.ts (38 lines - 0.3%)

</details>

</details>
    <details><summary>📂 **favorites** (214 lines - 1.5%)</summary>

      <details><summary>📂 **domain** (19 lines - 0.1%)</summary>

        - Favorite.ts (12 lines - 0.1%)
        - FavoriteRepository.ts (7 lines - 0%)

</details>
      <details><summary>📂 **infra** (49 lines - 0.3%)</summary>

        - FirestoreFavoriteAdminRepo.ts (14 lines - 0.1%)
        - FirestoreFavoriteRepo.ts (35 lines - 0.2%)

</details>
      <details><summary>📂 **ui** (146 lines - 1%)</summary>

        - FavoritesPage.module.css (71 lines - 0.5%)
        - FavoritesPage.tsx (75 lines - 0.5%)

</details>

</details>
    <details><summary>📂 **history** (185 lines - 1.3%)</summary>

      <details><summary>📂 **infra** (18 lines - 0.1%)</summary>

        - FirestoreHistoryRepo.ts (18 lines - 0.1%)

</details>
      <details><summary>📂 **models** (7 lines - 0%)</summary>

        - HistoryItem.ts (7 lines - 0%)

</details>
      <details><summary>📂 **ui** (142 lines - 1%)</summary>

        - HistoryList.module.css (61 lines - 0.4%)
        - HistoryList.tsx (81 lines - 0.6%)

</details>
      <details><summary>📂 **usecases** (18 lines - 0.1%)</summary>

        - saveUserHistory.ts (18 lines - 0.1%)

</details>

</details>
    <details><summary>📂 **home** (162 lines - 1.1%)</summary>

      <details><summary>📂 **ui** (162 lines - 1.1%)</summary>

        - Home.module.css (162 lines - 1.1%)

</details>

</details>
    <details><summary>📂 **library** (42 lines - 0.3%)</summary>

      <details><summary>📂 **favorites** (0 lines - 0%)</summary>

        - index.tsx (0 lines - 0%)

</details>
      <details><summary>📂 **story** (0 lines - 0%)</summary>

        - index.tsx (0 lines - 0%)

</details>
      <details><summary>📂 **ui** (42 lines - 0.3%)</summary>

        - LibraryHubPage.module.css (22 lines - 0.2%)
        - LibraryHubPage.tsx (20 lines - 0.1%)

</details>

</details>
    <details><summary>📂 **profile** (386 lines - 2.7%)</summary>

      <details><summary>📂 **model** (11 lines - 0.1%)</summary>

        - UserProfile.ts (11 lines - 0.1%)

</details>
      <details><summary>📂 **ui** (375 lines - 2.6%)</summary>

        - ProfilePage.js (214 lines - 1.5%)
        - ProfilePage.module.css (161 lines - 1.1%)

</details>

</details>
    <details><summary>📂 **quiz** (2272 lines - 15.8%)</summary>

      <details><summary>📂 **delf** (2080 lines - 14.5%)</summary>

        <details><summary>📂 **comprehensionOrale** (618 lines - 4.3%)</summary>

          <details><summary>📂 **infra** (45 lines - 0.3%)</summary>

            - fetchComprehensionTest.ts (17 lines - 0.1%)
            - officialAnswerKey.ts (28 lines - 0.2%)

</details>
          <details><summary>📂 **models** (29 lines - 0.2%)</summary>

            - ComprehensionTest.ts (29 lines - 0.2%)

</details>
          <details><summary>📂 **prompts** (0 lines - 0%)</summary>

            - buildComprehensionFeedbackPrompt.ts (0 lines - 0%)

</details>
          <details><summary>📂 **tests** (0 lines - 0%)</summary>

            - evaluateComprehensionAnswers.test.ts (0 lines - 0%)

</details>
          <details><summary>📂 **ui** (413 lines - 2.9%)</summary>

            - AudioFlowController.tsx (56 lines - 0.4%)
            <details><summary>📂 **components** (48 lines - 0.3%)</summary>

              - CorrectionTable.tsx (48 lines - 0.3%)

</details>
            - ComprehensionQuizPage.tsx (88 lines - 0.6%)
            - ComprehensionResults.tsx (33 lines - 0.2%)
            - CorrectionView.tsx (0 lines - 0%)
            - InstructionsPanel.tsx (42 lines - 0.3%)
            - QuestionBlock.tsx (37 lines - 0.3%)
            - ResultPanel.tsx (39 lines - 0.3%)
            <details><summary>📂 **styles** (70 lines - 0.5%)</summary>

              - ComprehensionResults.module.css (32 lines - 0.2%)
              - CorrectionTable.module.css (38 lines - 0.3%)

</details>

</details>
          <details><summary>📂 **usecases** (131 lines - 0.9%)</summary>

            - evaluateWithOfficialKey.ts (37 lines - 0.3%)
            - getScoreFeedback.ts (10 lines - 0.1%)
            - useComprehensionSession.ts (84 lines - 0.6%)

</details>

</details>
        <details><summary>📂 **hooks** (154 lines - 1.1%)</summary>

          - useComprehensionSession.js (61 lines - 0.4%)
          - useProductionEcriteSession.js (93 lines - 0.6%)

</details>
        <details><summary>📂 **infra** (170 lines - 1.2%)</summary>

          - evaluateComprehensionAnswers.js (20 lines - 0.1%)
          - evaluateWritingPrompt.js (22 lines - 0.2%)
          - fetchProductionEvaluation.js (12 lines - 0.1%)
          - fetchQuizText.js (27 lines - 0.2%)
          - parseComprehensionQuiz.js (29 lines - 0.2%)
          - parseWritingEvaluation.js (22 lines - 0.2%)
          - productionEcriteToPDF.js (38 lines - 0.3%)

</details>
        <details><summary>📂 **prompts** (73 lines - 0.5%)</summary>

          - comprehensionQuizPrompt.ts (38 lines - 0.3%)
          - writingEvaluationPrompt.js (35 lines - 0.2%)

</details>
        <details><summary>📂 **ui** (1041 lines - 7.2%)</summary>

          <details><summary>📂 **comprehensionEcrite** (179 lines - 1.2%)</summary>

            - CorrectionPanel.js (16 lines - 0.1%)
            - CorrectionPanel.module.css (23 lines - 0.2%)
            - QuestionBlock.js (32 lines - 0.2%)
            - QuestionBlock.module.css (37 lines - 0.3%)
            - QuizTimer.js (11 lines - 0.1%)
            - QuizTimer.module.css (12 lines - 0.1%)
            - TextViewer.js (18 lines - 0.1%)
            - TextViewer.module.css (30 lines - 0.2%)

</details>
          - DelfHubCard.js (18 lines - 0.1%)
          - DelfHubCard.module.css (41 lines - 0.3%)
          - FavoriteQuizPage.js (161 lines - 1.1%)
          <details><summary>📂 **productionEcrite** (642 lines - 4.5%)</summary>

            - CEFRRadarChart.js (71 lines - 0.5%)
            - CEFRRadarChart.module.css (8 lines - 0.1%)
            - EditorWithTimer.js (29 lines - 0.2%)
            - EditorWithTimer.module.css (75 lines - 0.5%)
            - EvaluationPanel.js (59 lines - 0.4%)
            - EvaluationPanel.module.css (73 lines - 0.5%)
            - ExportPDFButton.js (11 lines - 0.1%)
            - ExportPDFButton.module.css (18 lines - 0.1%)
            - PromptViewer.js (50 lines - 0.3%)
            - PromptViewer.module.css (61 lines - 0.4%)
            - ScoreBreakdown.js (27 lines - 0.2%)
            - ScoreBreakdown.module.css (32 lines - 0.2%)
            - TimerRing.js (38 lines - 0.3%)
            - TimerRing.module.css (23 lines - 0.2%)
            - TopicSelector.js (35 lines - 0.2%)
            - TopicSelector.module.css (32 lines - 0.2%)

</details>

</details>
        <details><summary>📂 **usecases** (24 lines - 0.2%)</summary>

          - generateComprehensionQuiz.ts (24 lines - 0.2%)

</details>

</details>
      <details><summary>📂 **favoritesquiz** (84 lines - 0.6%)</summary>

        <details><summary>📂 **prompts** (26 lines - 0.2%)</summary>

          - buildFavoriteQuizPrompt.ts (26 lines - 0.2%)

</details>
        <details><summary>📂 **usecases** (58 lines - 0.4%)</summary>

          - QuizController.ts (58 lines - 0.4%)

</details>

</details>
      <details><summary>📂 **hooks** (40 lines - 0.3%)</summary>

        - useQuiz.js (40 lines - 0.3%)

</details>
      <details><summary>📂 **shared** (68 lines - 0.5%)</summary>

        <details><summary>📂 **ui** (68 lines - 0.5%)</summary>

          - QuizCategoryCard.js (20 lines - 0.1%)
          - QuizCategoryCard.module.css (48 lines - 0.3%)

</details>

</details>

</details>
    <details><summary>📂 **related** (223 lines - 1.6%)</summary>

      <details><summary>📂 **infra** (85 lines - 0.6%)</summary>

        - fetchRelatedWords.js (85 lines - 0.6%)

</details>
      <details><summary>📂 **ui** (138 lines - 1%)</summary>

        - RelatedWordsGraph.jsx (138 lines - 1%)

</details>

</details>
    <details><summary>📂 **search** (15 lines - 0.1%)</summary>

      <details><summary>📂 **usecases** (15 lines - 0.1%)</summary>

        - classifyInput.ts (15 lines - 0.1%)

</details>

</details>
    <details><summary>📂 **sentence** (1555 lines - 10.8%)</summary>

      <details><summary>📂 **api** (19 lines - 0.1%)</summary>

        - handleSentenceQuery.js (19 lines - 0.1%)

</details>
      <details><summary>📂 **infra** (97 lines - 0.7%)</summary>

        - fetchUnifiedSentenceResponse.ts (42 lines - 0.3%)
        - transformGeminiSentenceResponse.ts (55 lines - 0.4%)

</details>
      <details><summary>📂 **models** (68 lines - 0.5%)</summary>

        - SentenceResponseModel.ts (68 lines - 0.5%)

</details>
      <details><summary>📂 **prompts** (110 lines - 0.8%)</summary>

        - unifiedPromptBuilder.ts (110 lines - 0.8%)

</details>
      <details><summary>📂 **ui** (1168 lines - 8.1%)</summary>

        <details><summary>📂 **components** (433 lines - 3%)</summary>

          - BackTranslationBlock.jsx (17 lines - 0.1%)
          - CompareSentencesBlock.jsx (20 lines - 0.1%)
          - ContextSuggestionBlock.jsx (15 lines - 0.1%)
          - EmotionLabelBlock.jsx (25 lines - 0.2%)
          - HardPartsBlock.jsx (21 lines - 0.1%)
          - IdiomExplainerBlock.jsx (25 lines - 0.2%)
          - SentenceDialogueBlock.tsx (112 lines - 0.8%)
          - SentenceHeaderBlock.jsx (36 lines - 0.3%)
          - SentenceStructureBlock.jsx (44 lines - 0.3%)
          - SentenceTrainerBlock.jsx (15 lines - 0.1%)
          - SimplifiedSentenceBlock.tsx (29 lines - 0.2%)
          - StepByStepDecoder.jsx (24 lines - 0.2%)
          - WordByWordBlock.jsx (50 lines - 0.3%)

</details>
        - SentenceResponse.module.css (132 lines - 0.9%)
        - SentenceResponse.tsx (96 lines - 0.7%)
        <details><summary>📂 **styles** (507 lines - 3.5%)</summary>

          - CompareSentencesBlock.module.css (31 lines - 0.2%)
          - ContextSuggestionBlock.module.css (11 lines - 0.1%)
          - EmotionLabelBlock.module.css (35 lines - 0.2%)
          - HardPartsBlock.module.css (36 lines - 0.3%)
          - IdiomExplainerBlock.module.css (28 lines - 0.2%)
          - SentenceDialogueBlock.module.css (37 lines - 0.3%)
          - SentenceHeaderBlock.module.css (32 lines - 0.2%)
          - sentenceSectionStyles.module.css (45 lines - 0.3%)
          - SentenceStructureBlock.module.css (55 lines - 0.4%)
          - SentenceTrainerBlock.module.css (11 lines - 0.1%)
          - SimplifiedSentenceBlock.module.css (21 lines - 0.1%)
          - StepByStepDecoder.module.css (32 lines - 0.2%)
          - WordByWordBlock.module.css (133 lines - 0.9%)

</details>

</details>
      <details><summary>📂 **usecases** (93 lines - 0.6%)</summary>

        - saveUserHistory.ts (12 lines - 0.1%)
        - SentenceController.ts (37 lines - 0.3%)
        - useSentenceTools.ts (44 lines - 0.3%)

</details>

</details>
    <details><summary>📂 **speak** (902 lines - 6.3%)</summary>

      <details><summary>📂 **hooks** (63 lines - 0.4%)</summary>

        - useSpeechRecognition.js (63 lines - 0.4%)

</details>
      <details><summary>📂 **infra** (209 lines - 1.5%)</summary>

        - continue.js (41 lines - 0.3%)
        - evaluateUserSpeech.js (44 lines - 0.3%)
        - fetchSpeakingPrompt.js (12 lines - 0.1%)
        - opening.js (23 lines - 0.2%)
        - prompt.js (24 lines - 0.2%)
        - saveSpeakingLog.js (38 lines - 0.3%)
        - suggest.js (27 lines - 0.2%)

</details>
      <details><summary>📂 **prompts** (35 lines - 0.2%)</summary>

        - speakingPromptBuilder.js (35 lines - 0.2%)

</details>
      <details><summary>📂 **ui** (595 lines - 4.1%)</summary>

        - SpeakingCoach.js (31 lines - 0.2%)
        - SpeakingLoop.js (142 lines - 1%)
        - SpeakingScenarioCard.js (22 lines - 0.2%)
        - SpeakingScenarioCard.module.css (45 lines - 0.3%)
        - SpeakingSessionPage.js (250 lines - 1.7%)
        - SpeakingSessionPage.module.css (59 lines - 0.4%)
        - SpeakPage.module.css (46 lines - 0.3%)

</details>

</details>
    <details><summary>📂 **story** (1271 lines - 8.8%)</summary>

      <details><summary>📂 **domain** (87 lines - 0.6%)</summary>

        - Story.ts (55 lines - 0.4%)
        - StoryConfig.ts (23 lines - 0.2%)
        - StoryRepository.ts (9 lines - 0.1%)

</details>
      <details><summary>📂 **infra** (131 lines - 0.9%)</summary>

        - FirestoreStoryRepo.ts (83 lines - 0.6%)
        - saveStory.ts (12 lines - 0.1%)
        - sendStoryPromptToGemini.ts (36 lines - 0.3%)

</details>
      <details><summary>📂 **prompts** (43 lines - 0.3%)</summary>

        - buildStoryPrompt.ts (43 lines - 0.3%)

</details>
      <details><summary>📂 **ui** (921 lines - 6.4%)</summary>

        <details><summary>📂 **components** (177 lines - 1.2%)</summary>

          - PlaceholderCard.tsx (12 lines - 0.1%)
          - StoryCard.tsx (72 lines - 0.5%)
          - StoryGeneratorForm.tsx (93 lines - 0.6%)

</details>
        <details><summary>📂 **hooks** (54 lines - 0.4%)</summary>

          - useGenerateStoryFlow.ts (54 lines - 0.4%)

</details>
        <details><summary>📂 **pages** (271 lines - 1.9%)</summary>

          - StoryFullView.tsx (130 lines - 0.9%)
          - StoryGeneratorPage.tsx (73 lines - 0.5%)
          - StoryPage.tsx (68 lines - 0.5%)

</details>
        <details><summary>📂 **styles** (419 lines - 2.9%)</summary>

          - StoryCard.module.css (78 lines - 0.5%)
          - StoryFullView.module.css (149 lines - 1%)
          - StoryGallery.module.css (52 lines - 0.4%)
          - StoryGeneratorForm.module.css (46 lines - 0.3%)
          - StoryGeneratorPage.module.css (94 lines - 0.7%)

</details>

</details>
      <details><summary>📂 **usecases** (89 lines - 0.6%)</summary>

        - deleteStory.ts (6 lines - 0%)
        - generateStory.ts (26 lines - 0.2%)
        - getInitialStoryData.ts (15 lines - 0.1%)
        - getUserFavoritesForStory.ts (7 lines - 0%)
        - getUserStories.ts (7 lines - 0%)
        - parseStoryGeminiResponse.ts (28 lines - 0.2%)

</details>

</details>
    <details><summary>📂 **word** (2206 lines - 15.3%)</summary>

      <details><summary>📂 **infra** (251 lines - 1.7%)</summary>

        - cleanAndClassify.js (7 lines - 0%)
        - fetchGeminiWordResponse.js (34 lines - 0.2%)
        - handleGeminiError.js (19 lines - 0.1%)
        - parseGeminiResponse.js (172 lines - 1.2%)
        <details><summary>📂 **scrapers** (19 lines - 0.1%)</summary>

          - scrapeLarousseSynAnto.js (19 lines - 0.1%)

</details>

</details>
      <details><summary>📂 **prompts** (218 lines - 1.5%)</summary>

        - generateWordPrompt.ts (171 lines - 1.2%)
        - rephrasePrompt.js (47 lines - 0.3%)

</details>
      <details><summary>📂 **ui** (1706 lines - 11.9%)</summary>

        <details><summary>📂 **components** (636 lines - 4.4%)</summary>

          <details><summary>📂 **definition** (49 lines - 0.3%)</summary>

            - WordDefinitionBlock.jsx (49 lines - 0.3%)

</details>
          <details><summary>📂 **dialogue** (171 lines - 1.2%)</summary>

            - DialogueSection.js (121 lines - 0.8%)
            - WordDialogueBlock.jsx (50 lines - 0.3%)

</details>
          <details><summary>📂 **expressions** (18 lines - 0.1%)</summary>

            - WordExpressionsBlock.jsx (18 lines - 0.1%)

</details>
          <details><summary>📂 **family** (27 lines - 0.2%)</summary>

            - WordFamilyBlock.jsx (27 lines - 0.2%)

</details>
          <details><summary>📂 **grammar** (79 lines - 0.5%)</summary>

            - WordGrammarBlock.jsx (79 lines - 0.5%)

</details>
          <details><summary>📂 **header** (57 lines - 0.4%)</summary>

            - WordHeader.jsx (57 lines - 0.4%)

</details>
          <details><summary>📂 **relations** (83 lines - 0.6%)</summary>

            - WordSynAntBlock.jsx (44 lines - 0.3%)
            - WordVocabularyBlock.jsx (39 lines - 0.3%)

</details>
          <details><summary>📂 **shared** (16 lines - 0.1%)</summary>

            - TopicSelector.jsx (16 lines - 0.1%)

</details>
          <details><summary>📂 **themes** (21 lines - 0.1%)</summary>

            - WordThemesBlock.jsx (21 lines - 0.1%)

</details>
          <details><summary>📂 **translation** (40 lines - 0.3%)</summary>

            - WordTranslationBlock.jsx (40 lines - 0.3%)

</details>
          <details><summary>📂 **WordHeaderBlock** (75 lines - 0.5%)</summary>

            - WordHeaderBlock.jsx (75 lines - 0.5%)

</details>

</details>
        - FormattedResponse.js (62 lines - 0.4%)
        <details><summary>📂 **styles** (782 lines - 5.4%)</summary>

          - sharedSectionStyles.module.css (23 lines - 0.2%)
          - WordDefinitionBlock.module.css (78 lines - 0.5%)
          - WordDialogueBlock.module.css (41 lines - 0.3%)
          - WordExpressionsBlock.module.css (30 lines - 0.2%)
          - WordExtrasBlock.module.css (93 lines - 0.6%)
          - WordFamilyBlock.module.css (64 lines - 0.4%)
          - WordGrammarBlock.module.css (62 lines - 0.4%)
          - WordHeader.module.css (170 lines - 1.2%)
          - WordHeaderBlock.module.css (123 lines - 0.9%)
          - WordResponse.module.css (32 lines - 0.2%)
          - WordTranslationBlock.module.css (44 lines - 0.3%)
          - WordVocabularyBlock.module.css (22 lines - 0.2%)

</details>
        - WordContentView.jsx (127 lines - 0.9%)
        - WordController.jsx (99 lines - 0.7%)

</details>
      <details><summary>📂 **usecases** (31 lines - 0.2%)</summary>

        - fetchSynAntoFromWeb.js (6 lines - 0%)
        - SearchController.ts (25 lines - 0.2%)

</details>

</details>
    <details><summary>📂 **youglish** (283 lines - 2%)</summary>

      <details><summary>📂 **infra** (52 lines - 0.4%)</summary>

        - youglishApi.ts (52 lines - 0.4%)

</details>
      <details><summary>📂 **ui** (193 lines - 1.3%)</summary>

        - YouglishMiniPlayer.tsx (28 lines - 0.2%)
        - YouglishModalPlayer.tsx (61 lines - 0.4%)
        - YouglishPanel.module.css (104 lines - 0.7%)

</details>
      <details><summary>📂 **usecases** (38 lines - 0.3%)</summary>

        - initYouglishWidget.ts (38 lines - 0.3%)

</details>

</details>

</details>
  <details><summary>📂 **infrastructure** (152 lines - 1.1%)</summary>

    <details><summary>📂 **firebase** (108 lines - 0.8%)</summary>

      - favoritesAdmin.js (17 lines - 0.1%)
      - firebaseAdmin.js (16 lines - 0.1%)
      - firebaseClient.js (20 lines - 0.1%)
      - firestoreAdmin.ts (27 lines - 0.2%)
      - firestoreClient.ts (28 lines - 0.2%)

</details>
    <details><summary>📂 **gemini** (44 lines - 0.3%)</summary>

      - sendToGemini.js (44 lines - 0.3%)

</details>

</details>
  <details><summary>📂 **pages** (1345 lines - 9.4%)</summary>

    - _app.js (32 lines - 0.2%)
    - _document.js (13 lines - 0.1%)
    <details><summary>📂 **api** (911 lines - 6.3%)</summary>

      - annotate.js (8 lines - 0.1%)
      <details><summary>📂 **comprehension** (42 lines - 0.3%)</summary>

        - evaluate.js (27 lines - 0.2%)
        - generate.js (15 lines - 0.1%)

</details>
      - continueStory.js (32 lines - 0.2%)
      - definitionQuiz.js (33 lines - 0.2%)
      - evaluateSpeech.js (89 lines - 0.6%)
      - explainGrammar.js (30 lines - 0.2%)
      - explainMistake.js (30 lines - 0.2%)
      <details><summary>📂 **favorites** (24 lines - 0.2%)</summary>

        - get.ts (10 lines - 0.1%)
        - remove.ts (14 lines - 0.1%)

</details>
      <details><summary>📂 **gemini** (17 lines - 0.1%)</summary>

        - evaluate.js (17 lines - 0.1%)

</details>
      - gemini.ts (70 lines - 0.5%)
      - getRelatedWords.js (31 lines - 0.2%)
      <details><summary>📂 **history** (48 lines - 0.3%)</summary>

        - fetch.ts (26 lines - 0.2%)
        - save.ts (22 lines - 0.2%)

</details>
      - hoverInfo.js (20 lines - 0.1%)
      - image.js (82 lines - 0.6%)
      <details><summary>📂 **playlists** (118 lines - 0.8%)</summary>

        - [playlistId].js (33 lines - 0.2%)
        - create.ts (27 lines - 0.2%)
        - delete.ts (22 lines - 0.2%)
        - index.js (14 lines - 0.1%)
        - rename.ts (22 lines - 0.2%)

</details>
      - sentence.js (1 lines - 0%)
      <details><summary>📂 **speaking** (15 lines - 0.1%)</summary>

        - saveLog.js (15 lines - 0.1%)

</details>
      - speakingPrompt.js (1 lines - 0%)
      <details><summary>📂 **story** (127 lines - 0.9%)</summary>

        - delete.ts (19 lines - 0.1%)
        - favorites.ts (25 lines - 0.2%)
        - generate.ts (36 lines - 0.3%)
        - initialData.ts (47 lines - 0.3%)

</details>
      - tts.js (40 lines - 0.3%)
      <details><summary>📂 **user** (18 lines - 0.1%)</summary>

        - profile.js (18 lines - 0.1%)

</details>
      <details><summary>📂 **word** (17 lines - 0.1%)</summary>

        - saveQuery.ts (17 lines - 0.1%)

</details>
      - word.js (18 lines - 0.1%)

</details>
    - index.js (2 lines - 0%)
    <details><summary>📂 **library** (79 lines - 0.5%)</summary>

      <details><summary>📂 **favorites** (4 lines - 0%)</summary>

        - index.js (4 lines - 0%)

</details>
      - index.js (4 lines - 0%)
      <details><summary>📂 **stories** (71 lines - 0.5%)</summary>

        - [id].tsx (50 lines - 0.3%)
        - generate.tsx (5 lines - 0%)
        - index.js (16 lines - 0.1%)

</details>

</details>
    <details><summary>📂 **profile** (5 lines - 0%)</summary>

      - index.js (5 lines - 0%)

</details>
    <details><summary>📂 **quiz** (228 lines - 1.6%)</summary>

      <details><summary>📂 **delf** (182 lines - 1.3%)</summary>

        <details><summary>📂 **comprehension-ecrite** (112 lines - 0.8%)</summary>

          - [level].js (38 lines - 0.3%)
          - index.js (74 lines - 0.5%)

</details>
        <details><summary>📂 **comprehension-orale** (22 lines - 0.2%)</summary>

          <details><summary>📂 **[level]** (22 lines - 0.2%)</summary>

            - [testId].tsx (22 lines - 0.2%)

</details>

</details>
        - index.js (46 lines - 0.3%)
        <details><summary>📂 **production-ecrite** (2 lines - 0%)</summary>

          - index.js (2 lines - 0%)

</details>

</details>
      - index.js (46 lines - 0.3%)

</details>
    <details><summary>📂 **search** (2 lines - 0%)</summary>

      - index.js (2 lines - 0%)

</details>
    <details><summary>📂 **speak** (73 lines - 0.5%)</summary>

      <details><summary>📂 **[level]** (19 lines - 0.1%)</summary>

        - [scenario].js (19 lines - 0.1%)

</details>
      - index.js (54 lines - 0.4%)

</details>

</details>
  <details><summary>📂 **presentation** (1178 lines - 8.2%)</summary>

    <details><summary>📂 **layout** (48 lines - 0.3%)</summary>

      - Layout.js (48 lines - 0.3%)

</details>
    <details><summary>📂 **pages** (541 lines - 3.8%)</summary>

      - HomePage.js (199 lines - 1.4%)
      - MiniStoryCard.tsx (98 lines - 0.7%)
      <details><summary>📂 **quiz** (83 lines - 0.6%)</summary>

        <details><summary>📂 **delf** (83 lines - 0.6%)</summary>

          - ProductionEcritePage.js (83 lines - 0.6%)

</details>

</details>
      - QuizPage.js (53 lines - 0.4%)
      - SearchPage.js (108 lines - 0.8%)

</details>
    <details><summary>📂 **styles** (589 lines - 4.1%)</summary>

      - HomePageRedesign.module.css (275 lines - 1.9%)
      - MiniStoryCard.module.css (79 lines - 0.5%)
      - QuizPage.module.css (136 lines - 0.9%)
      - Searchpage.module.css (99 lines - 0.7%)

</details>

</details>
  <details><summary>📂 **shared** (1726 lines - 12%)</summary>

    <details><summary>📂 **components** (924 lines - 6.4%)</summary>

      - FadeInOnScroll.js (16 lines - 0.1%)
      - FadeInWhenVisible.jsx (28 lines - 0.2%)
      - HoverableWord.jsx (33 lines - 0.2%)
      - HoverableWord.module.css (50 lines - 0.3%)
      - LanguageSelector.js (20 lines - 0.1%)
      <details><summary>📂 **library** (222 lines - 1.5%)</summary>

        - AddToLibraryModal.js (122 lines - 0.8%)
        - AddToLibraryModal.module.css (100 lines - 0.7%)

</details>
      - Navbar.js (59 lines - 0.4%)
      - Navbar.module.css (150 lines - 1%)
      - NotFoundBlock.js (36 lines - 0.3%)
      - ShimmerLoader.jsx (13 lines - 0.1%)
      - ShimmerLoader.module.css (45 lines - 0.3%)
      - Sidebar.js (83 lines - 0.6%)
      - Sidebar.module.css (169 lines - 1.2%)

</details>
    <details><summary>📂 **context** (70 lines - 0.5%)</summary>

      - ThemeContext.js (27 lines - 0.2%)
      - UserContext.js (43 lines - 0.3%)

</details>
    <details><summary>📂 **hooks** (208 lines - 1.4%)</summary>

      - useDefinitionQuiz.js (21 lines - 0.1%)
      - useExplainSection.js (20 lines - 0.1%)
      - useSearch.js (57 lines - 0.4%)
      - useTTSPlayer.js (75 lines - 0.5%)
      - useTypingEffect.js (35 lines - 0.2%)

</details>
    <details><summary>📂 **infra** (130 lines - 0.9%)</summary>

      - annotateTextClient.ts (10 lines - 0.1%)
      <details><summary>📂 **firebase** (97 lines - 0.7%)</summary>

        - favorites.js (50 lines - 0.3%)
        - firebase.js (47 lines - 0.3%)

</details>
      <details><summary>📂 **gemini** (23 lines - 0.2%)</summary>

        - fetchGemini.js (23 lines - 0.2%)

</details>

</details>
    <details><summary>📂 **prompts** (13 lines - 0.1%)</summary>

      - explanationPromptBuilder.ts (13 lines - 0.1%)

</details>
    <details><summary>📂 **styles** (289 lines - 2%)</summary>

      - colors.css (104 lines - 0.7%)
      - FormattedResponse.module.css (21 lines - 0.1%)
      - globals.css (80 lines - 0.6%)
      - Layout.module.css (84 lines - 0.6%)

</details>
    <details><summary>📂 **utils** (92 lines - 0.6%)</summary>

      <details><summary>📂 **helpers** (40 lines - 0.3%)</summary>

        - classifyInput.js (20 lines - 0.1%)
        - jsonRecovery.js (20 lines - 0.1%)

</details>
      <details><summary>📂 **pdf** (49 lines - 0.3%)</summary>

        - speakingSessionToPDF.js (49 lines - 0.3%)

</details>
      - tokenizeText.js (3 lines - 0%)

</details>

</details>
  <details><summary>📂 **types** (18 lines - 0.1%)</summary>

    - global.d.ts (18 lines - 0.1%)

</details>

</details>
<details><summary>📂 **utils** (109 lines - 0.8%)</summary>

  - graphBuilder.js (30 lines - 0.2%)
  <details><summary>📂 **helpers** (63 lines - 0.4%)</summary>

    - smartAnalyze.js (63 lines - 0.4%)

</details>
  <details><summary>📂 **openai** (16 lines - 0.1%)</summary>

    - imagePrompt.js (16 lines - 0.1%)

</details>

</details>

**Total Lines of Code:** 14376
