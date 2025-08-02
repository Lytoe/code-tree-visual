# Project Code Tree\n\n<details><summary>📂 **check-invalid-imports.js** (51 lines)</summary>

  <details><summary>📂 **check-invalid-imports.js** (51 lines)</summary>

    - check-invalid-imports.js (51 lines)

</details>

</details>
<details><summary>📂 **lint-colors.js** (38 lines)</summary>

  <details><summary>📂 **lint-colors.js** (38 lines)</summary>

    - lint-colors.js (38 lines)

</details>

</details>
<details><summary>📂 **next-env.d.ts** (5 lines)</summary>

  <details><summary>📂 **next-env.d.ts** (5 lines)</summary>

    - next-env.d.ts (5 lines)

</details>

</details>
<details><summary>📂 **src** (14173 lines)</summary>

  <details><summary>📂 **features** (9754 lines)</summary>

    <details><summary>📂 **classifier** (38 lines)</summary>

      <details><summary>📂 **hooks** (38 lines)</summary>

        - useClassifier.ts (38 lines)

</details>

</details>
    <details><summary>📂 **favorites** (214 lines)</summary>

      <details><summary>📂 **domain** (19 lines)</summary>

        - Favorite.ts (12 lines)
        - FavoriteRepository.ts (7 lines)

</details>
      <details><summary>📂 **infra** (49 lines)</summary>

        - FirestoreFavoriteAdminRepo.ts (14 lines)
        - FirestoreFavoriteRepo.ts (35 lines)

</details>
      <details><summary>📂 **ui** (146 lines)</summary>

        - FavoritesPage.module.css (71 lines)
        - FavoritesPage.tsx (75 lines)

</details>

</details>
    <details><summary>📂 **history** (185 lines)</summary>

      <details><summary>📂 **infra** (18 lines)</summary>

        - FirestoreHistoryRepo.ts (18 lines)

</details>
      <details><summary>📂 **models** (7 lines)</summary>

        - HistoryItem.ts (7 lines)

</details>
      <details><summary>📂 **ui** (142 lines)</summary>

        - HistoryList.module.css (61 lines)
        - HistoryList.tsx (81 lines)

</details>
      <details><summary>📂 **usecases** (18 lines)</summary>

        - saveUserHistory.ts (18 lines)

</details>

</details>
    <details><summary>📂 **home** (162 lines)</summary>

      <details><summary>📂 **ui** (162 lines)</summary>

        - Home.module.css (162 lines)

</details>

</details>
    <details><summary>📂 **library** (42 lines)</summary>

      <details><summary>📂 **favorites** (0 lines)</summary>

        - index.tsx (0 lines)

</details>
      <details><summary>📂 **story** (0 lines)</summary>

        - index.tsx (0 lines)

</details>
      <details><summary>📂 **ui** (42 lines)</summary>

        - LibraryHubPage.module.css (22 lines)
        - LibraryHubPage.tsx (20 lines)

</details>

</details>
    <details><summary>📂 **profile** (386 lines)</summary>

      <details><summary>📂 **model** (11 lines)</summary>

        - UserProfile.ts (11 lines)

</details>
      <details><summary>📂 **ui** (375 lines)</summary>

        - ProfilePage.js (214 lines)
        - ProfilePage.module.css (161 lines)

</details>

</details>
    <details><summary>📂 **quiz** (2272 lines)</summary>

      <details><summary>📂 **delf** (2080 lines)</summary>

        <details><summary>📂 **comprehensionOrale** (618 lines)</summary>

          <details><summary>📂 **infra** (45 lines)</summary>

            - fetchComprehensionTest.ts (17 lines)
            - officialAnswerKey.ts (28 lines)

</details>
          <details><summary>📂 **models** (29 lines)</summary>

            - ComprehensionTest.ts (29 lines)

</details>
          <details><summary>📂 **prompts** (0 lines)</summary>

            - buildComprehensionFeedbackPrompt.ts (0 lines)

</details>
          <details><summary>📂 **tests** (0 lines)</summary>

            - evaluateComprehensionAnswers.test.ts (0 lines)

</details>
          <details><summary>📂 **ui** (413 lines)</summary>

            - AudioFlowController.tsx (56 lines)
            <details><summary>📂 **components** (48 lines)</summary>

              - CorrectionTable.tsx (48 lines)

</details>
            - ComprehensionQuizPage.tsx (88 lines)
            - ComprehensionResults.tsx (33 lines)
            - CorrectionView.tsx (0 lines)
            - InstructionsPanel.tsx (42 lines)
            - QuestionBlock.tsx (37 lines)
            - ResultPanel.tsx (39 lines)
            <details><summary>📂 **styles** (70 lines)</summary>

              - ComprehensionResults.module.css (32 lines)
              - CorrectionTable.module.css (38 lines)

</details>

</details>
          <details><summary>📂 **usecases** (131 lines)</summary>

            - evaluateWithOfficialKey.ts (37 lines)
            - getScoreFeedback.ts (10 lines)
            - useComprehensionSession.ts (84 lines)

</details>

</details>
        <details><summary>📂 **hooks** (154 lines)</summary>

          - useComprehensionSession.js (61 lines)
          - useProductionEcriteSession.js (93 lines)

</details>
        <details><summary>📂 **infra** (170 lines)</summary>

          - evaluateComprehensionAnswers.js (20 lines)
          - evaluateWritingPrompt.js (22 lines)
          - fetchProductionEvaluation.js (12 lines)
          - fetchQuizText.js (27 lines)
          - parseComprehensionQuiz.js (29 lines)
          - parseWritingEvaluation.js (22 lines)
          - productionEcriteToPDF.js (38 lines)

</details>
        <details><summary>📂 **prompts** (73 lines)</summary>

          - comprehensionQuizPrompt.ts (38 lines)
          - writingEvaluationPrompt.js (35 lines)

</details>
        <details><summary>📂 **ui** (1041 lines)</summary>

          <details><summary>📂 **comprehensionEcrite** (179 lines)</summary>

            - CorrectionPanel.js (16 lines)
            - CorrectionPanel.module.css (23 lines)
            - QuestionBlock.js (32 lines)
            - QuestionBlock.module.css (37 lines)
            - QuizTimer.js (11 lines)
            - QuizTimer.module.css (12 lines)
            - TextViewer.js (18 lines)
            - TextViewer.module.css (30 lines)

</details>
          - DelfHubCard.js (18 lines)
          - DelfHubCard.module.css (41 lines)
          - FavoriteQuizPage.js (161 lines)
          <details><summary>📂 **productionEcrite** (642 lines)</summary>

            - CEFRRadarChart.js (71 lines)
            - CEFRRadarChart.module.css (8 lines)
            - EditorWithTimer.js (29 lines)
            - EditorWithTimer.module.css (75 lines)
            - EvaluationPanel.js (59 lines)
            - EvaluationPanel.module.css (73 lines)
            - ExportPDFButton.js (11 lines)
            - ExportPDFButton.module.css (18 lines)
            - PromptViewer.js (50 lines)
            - PromptViewer.module.css (61 lines)
            - ScoreBreakdown.js (27 lines)
            - ScoreBreakdown.module.css (32 lines)
            - TimerRing.js (38 lines)
            - TimerRing.module.css (23 lines)
            - TopicSelector.js (35 lines)
            - TopicSelector.module.css (32 lines)

</details>

</details>
        <details><summary>📂 **usecases** (24 lines)</summary>

          - generateComprehensionQuiz.ts (24 lines)

</details>

</details>
      <details><summary>📂 **favoritesquiz** (84 lines)</summary>

        <details><summary>📂 **prompts** (26 lines)</summary>

          - buildFavoriteQuizPrompt.ts (26 lines)

</details>
        <details><summary>📂 **usecases** (58 lines)</summary>

          - QuizController.ts (58 lines)

</details>

</details>
      <details><summary>📂 **hooks** (40 lines)</summary>

        - useQuiz.js (40 lines)

</details>
      <details><summary>📂 **shared** (68 lines)</summary>

        <details><summary>📂 **ui** (68 lines)</summary>

          - QuizCategoryCard.js (20 lines)
          - QuizCategoryCard.module.css (48 lines)

</details>

</details>

</details>
    <details><summary>📂 **related** (223 lines)</summary>

      <details><summary>📂 **infra** (85 lines)</summary>

        - fetchRelatedWords.js (85 lines)

</details>
      <details><summary>📂 **ui** (138 lines)</summary>

        - RelatedWordsGraph.jsx (138 lines)

</details>

</details>
    <details><summary>📂 **search** (15 lines)</summary>

      <details><summary>📂 **usecases** (15 lines)</summary>

        - classifyInput.ts (15 lines)

</details>

</details>
    <details><summary>📂 **sentence** (1555 lines)</summary>

      <details><summary>📂 **api** (19 lines)</summary>

        - handleSentenceQuery.js (19 lines)

</details>
      <details><summary>📂 **infra** (97 lines)</summary>

        - fetchUnifiedSentenceResponse.ts (42 lines)
        - transformGeminiSentenceResponse.ts (55 lines)

</details>
      <details><summary>📂 **models** (68 lines)</summary>

        - SentenceResponseModel.ts (68 lines)

</details>
      <details><summary>📂 **prompts** (110 lines)</summary>

        - unifiedPromptBuilder.ts (110 lines)

</details>
      <details><summary>📂 **ui** (1168 lines)</summary>

        <details><summary>📂 **components** (433 lines)</summary>

          - BackTranslationBlock.jsx (17 lines)
          - CompareSentencesBlock.jsx (20 lines)
          - ContextSuggestionBlock.jsx (15 lines)
          - EmotionLabelBlock.jsx (25 lines)
          - HardPartsBlock.jsx (21 lines)
          - IdiomExplainerBlock.jsx (25 lines)
          - SentenceDialogueBlock.tsx (112 lines)
          - SentenceHeaderBlock.jsx (36 lines)
          - SentenceStructureBlock.jsx (44 lines)
          - SentenceTrainerBlock.jsx (15 lines)
          - SimplifiedSentenceBlock.tsx (29 lines)
          - StepByStepDecoder.jsx (24 lines)
          - WordByWordBlock.jsx (50 lines)

</details>
        - SentenceResponse.module.css (132 lines)
        - SentenceResponse.tsx (96 lines)
        <details><summary>📂 **styles** (507 lines)</summary>

          - CompareSentencesBlock.module.css (31 lines)
          - ContextSuggestionBlock.module.css (11 lines)
          - EmotionLabelBlock.module.css (35 lines)
          - HardPartsBlock.module.css (36 lines)
          - IdiomExplainerBlock.module.css (28 lines)
          - SentenceDialogueBlock.module.css (37 lines)
          - SentenceHeaderBlock.module.css (32 lines)
          - sentenceSectionStyles.module.css (45 lines)
          - SentenceStructureBlock.module.css (55 lines)
          - SentenceTrainerBlock.module.css (11 lines)
          - SimplifiedSentenceBlock.module.css (21 lines)
          - StepByStepDecoder.module.css (32 lines)
          - WordByWordBlock.module.css (133 lines)

</details>

</details>
      <details><summary>📂 **usecases** (93 lines)</summary>

        - saveUserHistory.ts (12 lines)
        - SentenceController.ts (37 lines)
        - useSentenceTools.ts (44 lines)

</details>

</details>
    <details><summary>📂 **speak** (902 lines)</summary>

      <details><summary>📂 **hooks** (63 lines)</summary>

        - useSpeechRecognition.js (63 lines)

</details>
      <details><summary>📂 **infra** (209 lines)</summary>

        - continue.js (41 lines)
        - evaluateUserSpeech.js (44 lines)
        - fetchSpeakingPrompt.js (12 lines)
        - opening.js (23 lines)
        - prompt.js (24 lines)
        - saveSpeakingLog.js (38 lines)
        - suggest.js (27 lines)

</details>
      <details><summary>📂 **prompts** (35 lines)</summary>

        - speakingPromptBuilder.js (35 lines)

</details>
      <details><summary>📂 **ui** (595 lines)</summary>

        - SpeakingCoach.js (31 lines)
        - SpeakingLoop.js (142 lines)
        - SpeakingScenarioCard.js (22 lines)
        - SpeakingScenarioCard.module.css (45 lines)
        - SpeakingSessionPage.js (250 lines)
        - SpeakingSessionPage.module.css (59 lines)
        - SpeakPage.module.css (46 lines)

</details>

</details>
    <details><summary>📂 **story** (1271 lines)</summary>

      <details><summary>📂 **domain** (87 lines)</summary>

        - Story.ts (55 lines)
        - StoryConfig.ts (23 lines)
        - StoryRepository.ts (9 lines)

</details>
      <details><summary>📂 **infra** (131 lines)</summary>

        - FirestoreStoryRepo.ts (83 lines)
        - saveStory.ts (12 lines)
        - sendStoryPromptToGemini.ts (36 lines)

</details>
      <details><summary>📂 **prompts** (43 lines)</summary>

        - buildStoryPrompt.ts (43 lines)

</details>
      <details><summary>📂 **ui** (921 lines)</summary>

        <details><summary>📂 **components** (177 lines)</summary>

          - PlaceholderCard.tsx (12 lines)
          - StoryCard.tsx (72 lines)
          - StoryGeneratorForm.tsx (93 lines)

</details>
        <details><summary>📂 **hooks** (54 lines)</summary>

          - useGenerateStoryFlow.ts (54 lines)

</details>
        <details><summary>📂 **pages** (271 lines)</summary>

          - StoryFullView.tsx (130 lines)
          - StoryGeneratorPage.tsx (73 lines)
          - StoryPage.tsx (68 lines)

</details>
        <details><summary>📂 **styles** (419 lines)</summary>

          - StoryCard.module.css (78 lines)
          - StoryFullView.module.css (149 lines)
          - StoryGallery.module.css (52 lines)
          - StoryGeneratorForm.module.css (46 lines)
          - StoryGeneratorPage.module.css (94 lines)

</details>

</details>
      <details><summary>📂 **usecases** (89 lines)</summary>

        - deleteStory.ts (6 lines)
        - generateStory.ts (26 lines)
        - getInitialStoryData.ts (15 lines)
        - getUserFavoritesForStory.ts (7 lines)
        - getUserStories.ts (7 lines)
        - parseStoryGeminiResponse.ts (28 lines)

</details>

</details>
    <details><summary>📂 **word** (2206 lines)</summary>

      <details><summary>📂 **infra** (251 lines)</summary>

        - cleanAndClassify.js (7 lines)
        - fetchGeminiWordResponse.js (34 lines)
        - handleGeminiError.js (19 lines)
        - parseGeminiResponse.js (172 lines)
        <details><summary>📂 **scrapers** (19 lines)</summary>

          - scrapeLarousseSynAnto.js (19 lines)

</details>

</details>
      <details><summary>📂 **prompts** (218 lines)</summary>

        - generateWordPrompt.ts (171 lines)
        - rephrasePrompt.js (47 lines)

</details>
      <details><summary>📂 **ui** (1706 lines)</summary>

        <details><summary>📂 **components** (636 lines)</summary>

          <details><summary>📂 **definition** (49 lines)</summary>

            - WordDefinitionBlock.jsx (49 lines)

</details>
          <details><summary>📂 **dialogue** (171 lines)</summary>

            - DialogueSection.js (121 lines)
            - WordDialogueBlock.jsx (50 lines)

</details>
          <details><summary>📂 **expressions** (18 lines)</summary>

            - WordExpressionsBlock.jsx (18 lines)

</details>
          <details><summary>📂 **family** (27 lines)</summary>

            - WordFamilyBlock.jsx (27 lines)

</details>
          <details><summary>📂 **grammar** (79 lines)</summary>

            - WordGrammarBlock.jsx (79 lines)

</details>
          <details><summary>📂 **header** (57 lines)</summary>

            - WordHeader.jsx (57 lines)

</details>
          <details><summary>📂 **relations** (83 lines)</summary>

            - WordSynAntBlock.jsx (44 lines)
            - WordVocabularyBlock.jsx (39 lines)

</details>
          <details><summary>📂 **shared** (16 lines)</summary>

            - TopicSelector.jsx (16 lines)

</details>
          <details><summary>📂 **themes** (21 lines)</summary>

            - WordThemesBlock.jsx (21 lines)

</details>
          <details><summary>📂 **translation** (40 lines)</summary>

            - WordTranslationBlock.jsx (40 lines)

</details>
          <details><summary>📂 **WordHeaderBlock** (75 lines)</summary>

            - WordHeaderBlock.jsx (75 lines)

</details>

</details>
        - FormattedResponse.js (62 lines)
        <details><summary>📂 **styles** (782 lines)</summary>

          - sharedSectionStyles.module.css (23 lines)
          - WordDefinitionBlock.module.css (78 lines)
          - WordDialogueBlock.module.css (41 lines)
          - WordExpressionsBlock.module.css (30 lines)
          - WordExtrasBlock.module.css (93 lines)
          - WordFamilyBlock.module.css (64 lines)
          - WordGrammarBlock.module.css (62 lines)
          - WordHeader.module.css (170 lines)
          - WordHeaderBlock.module.css (123 lines)
          - WordResponse.module.css (32 lines)
          - WordTranslationBlock.module.css (44 lines)
          - WordVocabularyBlock.module.css (22 lines)

</details>
        - WordContentView.jsx (127 lines)
        - WordController.jsx (99 lines)

</details>
      <details><summary>📂 **usecases** (31 lines)</summary>

        - fetchSynAntoFromWeb.js (6 lines)
        - SearchController.ts (25 lines)

</details>

</details>
    <details><summary>📂 **youglish** (283 lines)</summary>

      <details><summary>📂 **infra** (52 lines)</summary>

        - youglishApi.ts (52 lines)

</details>
      <details><summary>📂 **ui** (193 lines)</summary>

        - YouglishMiniPlayer.tsx (28 lines)
        - YouglishModalPlayer.tsx (61 lines)
        - YouglishPanel.module.css (104 lines)

</details>
      <details><summary>📂 **usecases** (38 lines)</summary>

        - initYouglishWidget.ts (38 lines)

</details>

</details>

</details>
  <details><summary>📂 **infrastructure** (152 lines)</summary>

    <details><summary>📂 **firebase** (108 lines)</summary>

      - favoritesAdmin.js (17 lines)
      - firebaseAdmin.js (16 lines)
      - firebaseClient.js (20 lines)
      - firestoreAdmin.ts (27 lines)
      - firestoreClient.ts (28 lines)

</details>
    <details><summary>📂 **gemini** (44 lines)</summary>

      - sendToGemini.js (44 lines)

</details>

</details>
  <details><summary>📂 **pages** (1345 lines)</summary>

    - _app.js (32 lines)
    - _document.js (13 lines)
    <details><summary>📂 **api** (911 lines)</summary>

      - annotate.js (8 lines)
      <details><summary>📂 **comprehension** (42 lines)</summary>

        - evaluate.js (27 lines)
        - generate.js (15 lines)

</details>
      - continueStory.js (32 lines)
      - definitionQuiz.js (33 lines)
      - evaluateSpeech.js (89 lines)
      - explainGrammar.js (30 lines)
      - explainMistake.js (30 lines)
      <details><summary>📂 **favorites** (24 lines)</summary>

        - get.ts (10 lines)
        - remove.ts (14 lines)

</details>
      <details><summary>📂 **gemini** (17 lines)</summary>

        - evaluate.js (17 lines)

</details>
      - gemini.ts (70 lines)
      - getRelatedWords.js (31 lines)
      <details><summary>📂 **history** (48 lines)</summary>

        - fetch.ts (26 lines)
        - save.ts (22 lines)

</details>
      - hoverInfo.js (20 lines)
      - image.js (82 lines)
      <details><summary>📂 **playlists** (118 lines)</summary>

        - [playlistId].js (33 lines)
        - create.ts (27 lines)
        - delete.ts (22 lines)
        - index.js (14 lines)
        - rename.ts (22 lines)

</details>
      - sentence.js (1 lines)
      <details><summary>📂 **speaking** (15 lines)</summary>

        - saveLog.js (15 lines)

</details>
      - speakingPrompt.js (1 lines)
      <details><summary>📂 **story** (127 lines)</summary>

        - delete.ts (19 lines)
        - favorites.ts (25 lines)
        - generate.ts (36 lines)
        - initialData.ts (47 lines)

</details>
      - tts.js (40 lines)
      <details><summary>📂 **user** (18 lines)</summary>

        - profile.js (18 lines)

</details>
      <details><summary>📂 **word** (17 lines)</summary>

        - saveQuery.ts (17 lines)

</details>
      - word.js (18 lines)

</details>
    - index.js (2 lines)
    <details><summary>📂 **library** (79 lines)</summary>

      <details><summary>📂 **favorites** (4 lines)</summary>

        - index.js (4 lines)

</details>
      - index.js (4 lines)
      <details><summary>📂 **stories** (71 lines)</summary>

        - [id].tsx (50 lines)
        - generate.tsx (5 lines)
        - index.js (16 lines)

</details>

</details>
    <details><summary>📂 **profile** (5 lines)</summary>

      - index.js (5 lines)

</details>
    <details><summary>📂 **quiz** (228 lines)</summary>

      <details><summary>📂 **delf** (182 lines)</summary>

        <details><summary>📂 **comprehension-ecrite** (112 lines)</summary>

          - [level].js (38 lines)
          - index.js (74 lines)

</details>
        <details><summary>📂 **comprehension-orale** (22 lines)</summary>

          <details><summary>📂 **[level]** (22 lines)</summary>

            - [testId].tsx (22 lines)

</details>

</details>
        - index.js (46 lines)
        <details><summary>📂 **production-ecrite** (2 lines)</summary>

          - index.js (2 lines)

</details>

</details>
      - index.js (46 lines)

</details>
    <details><summary>📂 **search** (2 lines)</summary>

      - index.js (2 lines)

</details>
    <details><summary>📂 **speak** (73 lines)</summary>

      <details><summary>📂 **[level]** (19 lines)</summary>

        - [scenario].js (19 lines)

</details>
      - index.js (54 lines)

</details>

</details>
  <details><summary>📂 **presentation** (1178 lines)</summary>

    <details><summary>📂 **layout** (48 lines)</summary>

      - Layout.js (48 lines)

</details>
    <details><summary>📂 **pages** (541 lines)</summary>

      - HomePage.js (199 lines)
      - MiniStoryCard.tsx (98 lines)
      <details><summary>📂 **quiz** (83 lines)</summary>

        <details><summary>📂 **delf** (83 lines)</summary>

          - ProductionEcritePage.js (83 lines)

</details>

</details>
      - QuizPage.js (53 lines)
      - SearchPage.js (108 lines)

</details>
    <details><summary>📂 **styles** (589 lines)</summary>

      - HomePageRedesign.module.css (275 lines)
      - MiniStoryCard.module.css (79 lines)
      - QuizPage.module.css (136 lines)
      - Searchpage.module.css (99 lines)

</details>

</details>
  <details><summary>📂 **shared** (1726 lines)</summary>

    <details><summary>📂 **components** (924 lines)</summary>

      - FadeInOnScroll.js (16 lines)
      - FadeInWhenVisible.jsx (28 lines)
      - HoverableWord.jsx (33 lines)
      - HoverableWord.module.css (50 lines)
      - LanguageSelector.js (20 lines)
      <details><summary>📂 **library** (222 lines)</summary>

        - AddToLibraryModal.js (122 lines)
        - AddToLibraryModal.module.css (100 lines)

</details>
      - Navbar.js (59 lines)
      - Navbar.module.css (150 lines)
      - NotFoundBlock.js (36 lines)
      - ShimmerLoader.jsx (13 lines)
      - ShimmerLoader.module.css (45 lines)
      - Sidebar.js (83 lines)
      - Sidebar.module.css (169 lines)

</details>
    <details><summary>📂 **context** (70 lines)</summary>

      - ThemeContext.js (27 lines)
      - UserContext.js (43 lines)

</details>
    <details><summary>📂 **hooks** (208 lines)</summary>

      - useDefinitionQuiz.js (21 lines)
      - useExplainSection.js (20 lines)
      - useSearch.js (57 lines)
      - useTTSPlayer.js (75 lines)
      - useTypingEffect.js (35 lines)

</details>
    <details><summary>📂 **infra** (130 lines)</summary>

      - annotateTextClient.ts (10 lines)
      <details><summary>📂 **firebase** (97 lines)</summary>

        - favorites.js (50 lines)
        - firebase.js (47 lines)

</details>
      <details><summary>📂 **gemini** (23 lines)</summary>

        - fetchGemini.js (23 lines)

</details>

</details>
    <details><summary>📂 **prompts** (13 lines)</summary>

      - explanationPromptBuilder.ts (13 lines)

</details>
    <details><summary>📂 **styles** (289 lines)</summary>

      - colors.css (104 lines)
      - FormattedResponse.module.css (21 lines)
      - globals.css (80 lines)
      - Layout.module.css (84 lines)

</details>
    <details><summary>📂 **utils** (92 lines)</summary>

      <details><summary>📂 **helpers** (40 lines)</summary>

        - classifyInput.js (20 lines)
        - jsonRecovery.js (20 lines)

</details>
      <details><summary>📂 **pdf** (49 lines)</summary>

        - speakingSessionToPDF.js (49 lines)

</details>
      - tokenizeText.js (3 lines)

</details>

</details>
  <details><summary>📂 **types** (18 lines)</summary>

    - global.d.ts (18 lines)

</details>

</details>
<details><summary>📂 **utils** (109 lines)</summary>

  - graphBuilder.js (30 lines)
  <details><summary>📂 **helpers** (63 lines)</summary>

    - smartAnalyze.js (63 lines)

</details>
  <details><summary>📂 **openai** (16 lines)</summary>

    - imagePrompt.js (16 lines)

</details>

</details>

**Total Lines of Code:** 14376
