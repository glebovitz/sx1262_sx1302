# Project File Structure

│—— .git
│  │—— hooks
│  │  │—— applypatch-msg.sample
│  │  │—— commit-msg.sample
│  │  │—— fsmonitor-watchman.sample
│  │  │—— post-update.sample
│  │  │—— pre-applypatch.sample
│  │  │—— pre-commit.sample
│  │  │—— pre-merge-commit.sample
│  │  │—— pre-push.sample
│  │  │—— pre-rebase.sample
│  │  │—— pre-receive.sample
│  │  │—— prepare-commit-msg.sample
│  │  │—— push-to-checkout.sample
│  │  │—— sendemail-validate.sample
│  │  ╵—— update.sample
│  │—— info
│  │  ╵—— exclude
│  │—— logs
│  │  │—— refs
│  │  │  │—— heads
│  │  │  │  ╵—— main
│  │  │  ╵—— remotes
│  │  │  │  ╵—— origin
│  │  │  │  │  │—— HEAD
│  │  │  │  │  ╵—— main
│  │  ╵—— HEAD
│  │—— objects
│  │  │—— 09
│  │  │  ╵—— 9a8dcafc0069e684021aa074566c988e801a45
│  │  │—— 0f
│  │  │  ╵—— e9df35c8447ce9a069f78da385a3acaaeabe77
│  │  │—— 15
│  │  │  │—— 3f327b5d86f9a5d07c7a080d4f258b3b69d7b1
│  │  │  ╵—— 843a5cb1c275b7636089600085610503381d6e
│  │  │—— 17
│  │  │  ╵—— 1d92d745f293030e17469608cc51e57657b32d
│  │  │—— 19
│  │  │  ╵—— 6b5461bdd1e9b5449e1f2b7fd61385576bf713
│  │  │—— 1a
│  │  │  │—— 0798093c649d627be5baa201e0d4cbd86bb472
│  │  │  ╵—— c67ee9440fa2eb3a75852ebdf67582f6e01fc8
│  │  │—— 1c
│  │  │  ╵—— c0ce16836d221f4274e53a598ecd985239fc99
│  │  │—— 1e
│  │  │  ╵—— 4ef44c0c2cc82046b1fb28e8f3ee6b982ff161
│  │  │—— 24
│  │  │  ╵—— 1aeb993118dff90c1be92f9e7782af2241af95
│  │  │—— 26
│  │  │  ╵—— c2ccee17c012876a9d183d187e335c203f0848
│  │  │—— 2d
│  │  │  │—— 9a4268c133a948af8d5749d6c6313891ee9960
│  │  │  ╵—— bcac0aced125b97d5e7f4e710ee991e0152c32
│  │  │—— 2f
│  │  │  ╵—— 12aa396d4d73504e40c8072a81a91123221332
│  │  │—— 30
│  │  │  ╵—— 6b25382c303e9981d65936294ea23329ecf4ce
│  │  │—— 3b
│  │  │  ╵—— 9400544cba3eeca298f26ec800cd72e4145f10
│  │  │—— 42
│  │  │  │—— 20d402f6fcee6a203b0880b576e25bf21a13c3
│  │  │  ╵—— 3420911d8898f681a38277021f0c44dbfbc510
│  │  │—— 46
│  │  │  ╵—— 4f3d72b8d5dcbc582220d689a8ad13ad300d01
│  │  │—— 49
│  │  │  │—— e7e74e78acd633feab396d0675cadf63603791
│  │  │  ╵—— efc23d72824904d3d06a9db475171437df308f
│  │  │—— 4a
│  │  │  ╵—— 4d0ffc8c00c6161384c612f26632903250abdb
│  │  │—— 4e
│  │  │  ╵—— 75e2b19ba1a5d37bb21ce000936ca3cb7df54b
│  │  │—— 4f
│  │  │  ╵—— 398b9a3eb9b0dc7b0cebd0427e2a2d1790068a
│  │  │—— 52
│  │  │  ╵—— ccf183bc494b09e74291bda3585ec93e7b3b71
│  │  │—— 54
│  │  │  ╵—— b3c3b9415b2574b8f5fe275cf60eb26cf2426a
│  │  │—— 56
│  │  │  ╵—— e9e1f73fd13aa43bdc8e22dc9bdcb95eda0442
│  │  │—— 5a
│  │  │  │—— 3045727461361409e8e5c3a687e7bc9c3c0407
│  │  │  ╵—— bb146ef33cca7346e81a174af5204b83d10bb7
│  │  │—— 5e
│  │  │  ╵—— 24b5a5a3675ccc86bd1fd2442be8f0ac02325f
│  │  │—— 65
│  │  │  ╵—— a0ca27763e0658f19d34b60fa15694857b17ad
│  │  │—— 68
│  │  │  ╵—— 421b826331757796eda698bf1102ac83eb6396
│  │  │—— 69
│  │  │  ╵—— 051aaa1119bbff440ad4118282a29f8af6cd39
│  │  │—— 6a
│  │  │  ╵—— 3e420461e1fa9cb0335b8b3b6d213d9f934b30
│  │  │—— 6b
│  │  │  ╵—— 19fe092423d5022ada9e40bcffdab5439d2d1d
│  │  │—— 6c
│  │  │  ╵—— 234cf452cb5ba98d0db6fe230facb67a67f3cc
│  │  │—— 6f
│  │  │  ╵—— 74ba2dd3bda49af3463c838146bfa646f62a8e
│  │  │—— 70
│  │  │  ╵—— 14bcf561a1b09e085fc674e7932cdc44e6fda5
│  │  │—— 73
│  │  │  ╵—— 2cedafb2809f905c8127e347a69335cd7d6403
│  │  │—— 74
│  │  │  ╵—— dc498a1c9cf3ec5f5d956dfdd1703d3369bade
│  │  │—— 77
│  │  │  ╵—— 590b258b31c6bd7d30a95c33c47bf3daf2b064
│  │  │—— 7b
│  │  │  │—— 53a730130099457d592685e51d598ae0652f05
│  │  │  ╵—— bbc64c66db348adee4d1b220fcd2ec10c1ff7f
│  │  │—— 80
│  │  │  ╵—— b72ff8dcbe469aa554f02c2ea4992da91f66a6
│  │  │—— 84
│  │  │  │—— 0ba086af53559913e1b8ddd34c01637b46b8da
│  │  │  │—— 272849d31ab08f2973cfa87636df7fdda664b2
│  │  │  │—— 2f6938959625f42375b73f03a9ca1eb7e3b486
│  │  │  ╵—— 83f71e575ce724f9a57273bbf3d83f196b2b05
│  │  │—— 8d
│  │  │  ╵—— caef0bebbc7df2ceb52f3ed692697157aeebbb
│  │  │—— 91
│  │  │  ╵—— 728e01579ae041e14dd84e06a25a5f373881f9
│  │  │—— 97
│  │  │  ╵—— 8c50c0a85cd3b84d58828dfb8c7d1fff641a5d
│  │  │—— 9a
│  │  │  │—— 812c71b649572148d6190e24f819658ee2339f
│  │  │  ╵—— ae479f6a8634084dfa7d2bad32fc642941873e
│  │  │—— 9b
│  │  │  ╵—— ead7d5f270f83d8249161fba3ce5f01a118655
│  │  │—— 9e
│  │  │  │—— c5b2e1492c7541472721e8b124dfe5942ca074
│  │  │  ╵—— ee6122513b22cfb00cb70d9a3552d7d2655520
│  │  │—— a0
│  │  │  ╵—— 09e28214a19ee908c8cc1f698cf9ce6511c954
│  │  │—— a3
│  │  │  ╵—— ca6540c53ddfdc074d04e0b7b346888c3827fd
│  │  │—— a4
│  │  │  ╵—— 60abf53e2e21a0f0d12da9c5bc7b0f1e45daae
│  │  │—— a5
│  │  │  ╵—— d02e1f2b623e4f5dae058f871253239af59bf6
│  │  │—— a9
│  │  │  ╵—— 25c422c95575d9097224aa62001e1fb3e4dfe6
│  │  │—— aa
│  │  │  ╵—— e55df410c1b1ee3fd94ec09550c473bc296126
│  │  │—— ad
│  │  │  │—— b6be2e7533dbb389babfabc5203954925f7468
│  │  │  ╵—— fb548ea09893e86a2f55952da40183d6465879
│  │  │—— ae
│  │  │  │—— 467ac520eb46dd0c82075747e5ca1d1e592e9d
│  │  │  ╵—— e98a1336f19d2fa1bab1035389ac4f2e347a4b
│  │  │—— b1
│  │  │  ╵—— 8b00cf6003ba1934d8b3313600b4baf657cd81
│  │  │—— b2
│  │  │  ╵—— 11f96addb9b76212dd179b11bd056fa898281b
│  │  │—— b3
│  │  │  ╵—— 04d4396b8561844d78868888a275b3a7c357d1
│  │  │—— b4
│  │  │  ╵—— 60d1573abf1f4f1d0474984dd688e934704f42
│  │  │—— b7
│  │  │  ╵—— c3c5a0c87bb212e0fc2a2483257ae30f41f145
│  │  │—— b8
│  │  │  ╵—— 8cf26131e681aa60f02f6aaf6d99548c80ef7b
│  │  │—— b9
│  │  │  ╵—— 698fda2dfe37468e57f7ff4ab49e17a6a6c597
│  │  │—— c1
│  │  │  ╵—— 75ba4254bef7d7d5c9fd1bf0245636fb490f7f
│  │  │—— c3
│  │  │  ╵—— 12684aaccef9ba3f6aa9bfca31f09ef1b745d7
│  │  │—— c9
│  │  │  ╵—— 439e3cd730d05ab1ce425af90b97778f270759
│  │  │—— ca
│  │  │  ╵—— 482a6c63079e7e8e70b9e5b6b4a43c1ea6bd0f
│  │  │—— cb
│  │  │  │—— 28a9627d5b46c111b80c00bb251fef5e8514d0
│  │  │  ╵—— aa7c30dd36b3ba6d36a42dd965c167533ff96b
│  │  │—— cc
│  │  │  ╵—— d7ba32ae324c764c491db57c819a4529b9dc09
│  │  │—— cd
│  │  │  ╵—— b57a03c79ee764ea9c660228385edcfd343e74
│  │  │—— ce
│  │  │  ╵—— 75f01d594932426478f912533b2c2bfaa6f5c1
│  │  │—— cf
│  │  │  ╵—— 9e87072df7d21eda60dac6aa27da29c2142e2b
│  │  │—— d3
│  │  │  ╵—— 13555b5a79769c2e3164ab9fab60a91ac31a84
│  │  │—— d4
│  │  │  ╵—— 88e0740efd9f8f1280c7ac3666fa9e9e985487
│  │  │—— d5
│  │  │  ╵—— 4186abc555e6d9656e84e6d83383ac3e15c347
│  │  │—— d7
│  │  │  ╵—— d1f6bd61d4d3bf3902548eb9ab463453cfc7a5
│  │  │—— d9
│  │  │  ╵—— 243c55f71b9269e6ff841b4dc794c18eae32ec
│  │  │—— db
│  │  │  │—— bc43fa39f209be0deabba5446fb1e30308d25b
│  │  │  ╵—— c1b297cdd48940d8ebd663167d954ca7b40419
│  │  │—— dc
│  │  │  ╵—— 7b1673c5d1867421817a39dc7909ef7941ce12
│  │  │—— dd
│  │  │  ╵—— 98a03d34171a7e030873fd15dd7607de61f6e4
│  │  │—— e0
│  │  │  │—— 435b5dfe7ae42ec0eb51fb93e093d8b7cfb22d
│  │  │  ╵—— b318a59e09b0af522db9dcb445b61436021185
│  │  │—— e6
│  │  │  ╵—— 9de29bb2d1d6434b8b29ae775ad8c2e48c5391
│  │  │—— eb
│  │  │  ╵—— 6e96e11ba727f949f93c1a0eba3e8ef4cf904c
│  │  │—— ed
│  │  │  ╵—— dda803b9b2627515d4133a9d795e5e4b570b89
│  │  │—— ee
│  │  │  │—— d299c2e290127085a996b8a8392b4d0f7399a3
│  │  │  ╵—— e8963cb6f53efc85f5f05144e5520939be2795
│  │  │—— f0
│  │  │  ╵—— 2be1665a68725727168d45c503e0aaf6fd72bc
│  │  │—— f4
│  │  │  ╵—— c60cbf8235b5a7a54df2961503e734a1448b9a
│  │  │—— f9
│  │  │  ╵—— 3e3a1a1525fb5b91020da86e44810c87a2d7bc
│  │  │—— fc
│  │  │  ╵—— 71cc7a0b7055c7f93a3d2cb03b8af8639966a7
│  │  │—— info
│  │  ╵—— pack
│  │—— refs
│  │  │—— heads
│  │  │  ╵—— main
│  │  │—— remotes
│  │  │  ╵—— origin
│  │  │  │  │—— HEAD
│  │  │  │  ╵—— main
│  │  ╵—— tags
│  │—— COMMIT_EDITMSG
│  │—— config
│  │—— description
│  │—— FETCH_HEAD
│  │—— HEAD
│  │—— index
│  ╵—— ORIG_HEAD
│—— sx1262-driver
│  │—— core
│  │  │—— event_emitter.py
│  │  ╵—— __init__.py
│  │—— base.py
│  │—— sx1262.py
│  │—— sx1262_api.py
│  │—— sx1262_common.py
│  │—— sx1262_constants.py
│  │—— sx1262_hardware.py
│  │—— sx1262_interrupt.py
│  │—— sx1262_modem.py
│  │—— sx1262_receive.py
│  │—— sx1262_status.py
│  │—— sx1262_transmit.py
│  │—— sx1262_vars.py
│  ╵—— __init__.py
│—— .bashrc
│—— .gitignore
│—— ERRARA.md
│—— filestructure.md
│—— filestructure.ps1
│—— LICENSE
│—— listener.py
│—— pyproject.toml
│—— README.md
│—— sx1262-driver.code-workspace
╵—— tx.py
