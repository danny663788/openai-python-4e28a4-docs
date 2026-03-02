.
├── Brewfile
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── SECURITY.md
├── api.md
├── bin
│   ├── check-release-environment
│   └── publish-pypi
├── examples
│   ├── async_demo.py
│   ├── audio.py
│   ├── azure.py
│   ├── azure_ad.py
│   ├── demo.py
│   ├── generate_file.sh
│   ├── image_stream.py
│   ├── module_client.py
│   ├── parsing.py
│   ├── parsing_stream.py
│   ├── parsing_tools.py
│   ├── parsing_tools_stream.py
│   ├── picture.py
│   ├── realtime
│   │   ├── audio_util.py
│   │   ├── azure_realtime.py
│   │   └── push_to_talk_app.py
│   ├── responses
│   │   ├── __init__.py
│   │   ├── background.py
│   │   ├── background_async.py
│   │   ├── background_streaming.py
│   │   ├── background_streaming_async.py
│   │   ├── streaming.py
│   │   ├── streaming_tools.py
│   │   ├── structured_outputs.py
│   │   └── structured_outputs_tools.py
│   ├── speech_to_text.py
│   ├── streaming.py
│   ├── text_to_speech.py
│   └── uploads.py
├── helpers.md
├── mypy.ini
├── noxfile.py
├── pyproject.toml
├── release-please-config.json
├── requirements-dev.lock
├── requirements.lock
├── scripts
│   ├── bootstrap
│   ├── detect-breaking-changes
│   ├── detect-breaking-changes.py
│   ├── format
│   ├── lint
│   ├── mock
│   ├── test
│   └── utils
│       ├── ruffen-docs.py
│       └── upload-artifact.sh
├── src
│   └── openai
│       ├── __init__.py
│       ├── __main__.py
│       ├── _base_client.py
│       ├── _client.py
│       ├── _compat.py
│       ├── _constants.py
│       ├── _exceptions.py
│       ├── _extras
│       │   ├── __init__.py
│       │   ├── _common.py
│       │   ├── numpy_proxy.py
│       │   ├── pandas_proxy.py
│       │   └── sounddevice_proxy.py
│       ├── _files.py
│       ├── _legacy_response.py
│       ├── _models.py
│       ├── _module_client.py
│       ├── _qs.py
│       ├── _resource.py
│       ├── _response.py
│       ├── _streaming.py
│       ├── _types.py
│       ├── _utils
│       │   ├── __init__.py
│       │   ├── _logs.py
│       │   ├── _proxy.py
│       │   ├── _reflection.py
│       │   ├── _resources_proxy.py
│       │   ├── _streams.py
│       │   ├── _sync.py
│       │   ├── _transform.py
│       │   ├── _typing.py
│       │   └── _utils.py
│       ├── _version.py
│       ├── cli
│       │   ├── __init__.py
│       │   ├── _api
│       │   │   ├── __init__.py
│       │   │   ├── _main.py
│       │   │   ├── audio.py
│       │   │   ├── chat
│       │   │   │   ├── __init__.py
│       │   │   │   └── completions.py
│       │   │   ├── completions.py
│       │   │   ├── files.py
│       │   │   ├── fine_tuning
│       │   │   │   ├── __init__.py
│       │   │   │   └── jobs.py
│       │   │   ├── image.py
│       │   │   └── models.py
│       │   ├── _cli.py
│       │   ├── _errors.py
│       │   ├── _models.py
│       │   ├── _progress.py
│       │   ├── _tools
│       │   │   ├── __init__.py
│       │   │   ├── _main.py
│       │   │   ├── fine_tunes.py
│       │   │   └── migrate.py
│       │   └── _utils.py
│       ├── helpers
│       │   ├── __init__.py
│       │   ├── local_audio_player.py
│       │   └── microphone.py
│       ├── lib
│       │   ├── __init__.py
│       │   ├── _old_api.py
│       │   ├── _parsing
│       │   │   ├── __init__.py
│       │   │   ├── _completions.py
│       │   │   └── _responses.py
│       │   ├── _pydantic.py
│       │   ├── _tools.py
│       │   ├── _validators.py
│       │   ├── azure.py
│       │   └── streaming
│       │       ├── __init__.py
│       │       ├── _assistants.py
│       │       ├── _deltas.py
│       │       ├── chat
│       │       │   ├── __init__.py
│       │       │   ├── _completions.py
│       │       │   ├── _events.py
│       │       │   └── _types.py
│       │       └── responses
│       │           ├── __init__.py
│       │           ├── _events.py
│       │           ├── _responses.py
│       │           └── _types.py
│       ├── pagination.py
│       ├── py.typed
│       ├── resources
│       │   ├── __init__.py
│       │   ├── audio
│       │   │   ├── __init__.py
│       │   │   ├── audio.py
│       │   │   ├── speech.py
│       │   │   ├── transcriptions.py
│       │   │   └── translations.py
│       │   ├── batches.py
│       │   ├── beta
│       │   │   ├── __init__.py
│       │   │   ├── assistants.py
│       │   │   ├── beta.py
│       │   │   ├── realtime
│       │   │   │   ├── __init__.py
│       │   │   │   ├── realtime.py
│       │   │   │   ├── sessions.py
│       │   │   │   └── transcription_sessions.py
│       │   │   └── threads
│       │   │       ├── __init__.py
│       │   │       ├── messages.py
│       │   │       ├── runs
│       │   │       │   ├── __init__.py
│       │   │       │   ├── runs.py
│       │   │       │   └── steps.py
│       │   │       └── threads.py
│       │   ├── chat
│       │   │   ├── __init__.py
│       │   │   ├── chat.py
│       │   │   └── completions
│       │   │       ├── __init__.py
│       │   │       ├── completions.py
│       │   │       └── messages.py
│       │   ├── completions.py
│       │   ├── containers
│       │   │   ├── __init__.py
│       │   │   ├── containers.py
│       │   │   └── files
│       │   │       ├── __init__.py
│       │   │       ├── content.py
│       │   │       └── files.py
│       │   ├── conversations
│       │   │   ├── __init__.py
│       │   │   ├── conversations.py
│       │   │   └── items.py
│       │   ├── embeddings.py
│       │   ├── evals
│       │   │   ├── __init__.py
│       │   │   ├── evals.py
│       │   │   └── runs
│       │   │       ├── __init__.py
│       │   │       ├── output_items.py
│       │   │       └── runs.py
│       │   ├── files.py
│       │   ├── fine_tuning
│       │   │   ├── __init__.py
│       │   │   ├── alpha
│       │   │   │   ├── __init__.py
│       │   │   │   ├── alpha.py
│       │   │   │   └── graders.py
│       │   │   ├── checkpoints
│       │   │   │   ├── __init__.py
│       │   │   │   ├── checkpoints.py
│       │   │   │   └── permissions.py
│       │   │   ├── fine_tuning.py
│       │   │   └── jobs
│       │   │       ├── __init__.py
│       │   │       ├── checkpoints.py
│       │   │       └── jobs.py
│       │   ├── images.py
│       │   ├── models.py
│       │   ├── moderations.py
│       │   ├── responses
│       │   │   ├── __init__.py
│       │   │   ├── input_items.py
│       │   │   └── responses.py
│       │   ├── uploads
│       │   │   ├── __init__.py
│       │   │   ├── parts.py
│       │   │   └── uploads.py
│       │   ├── vector_stores
│       │   │   ├── __init__.py
│       │   │   ├── file_batches.py
│       │   │   ├── files.py
│       │   │   └── vector_stores.py
│       │   └── webhooks.py
│       ├── types
│       │   ├── __init__.py
│       │   ├── audio
│       │   │   ├── __init__.py
│       │   │   ├── speech_create_params.py
│       │   │   ├── speech_model.py
│       │   │   ├── transcription.py
│       │   │   ├── transcription_create_params.py
│       │   │   ├── transcription_create_response.py
│       │   │   ├── transcription_include.py
│       │   │   ├── transcription_segment.py
│       │   │   ├── transcription_stream_event.py
│       │   │   ├── transcription_text_delta_event.py
│       │   │   ├── transcription_text_done_event.py
│       │   │   ├── transcription_verbose.py
│       │   │   ├── transcription_word.py
│       │   │   ├── translation.py
│       │   │   ├── translation_create_params.py
│       │   │   ├── translation_create_response.py
│       │   │   └── translation_verbose.py
│       │   ├── audio_model.py
│       │   ├── audio_response_format.py
│       │   ├── auto_file_chunking_strategy_param.py
│       │   ├── batch.py
│       │   ├── batch_create_params.py
│       │   ├── batch_error.py
│       │   ├── batch_list_params.py
│       │   ├── batch_request_counts.py
│       │   ├── beta
│       │   │   ├── __init__.py
│       │   │   ├── assistant.py
│       │   │   ├── assistant_create_params.py
│       │   │   ├── assistant_deleted.py
│       │   │   ├── assistant_list_params.py
│       │   │   ├── assistant_response_format_option.py
│       │   │   ├── assistant_response_format_option_param.py
│       │   │   ├── assistant_stream_event.py
│       │   │   ├── assistant_tool.py
│       │   │   ├── assistant_tool_choice.py
│       │   │   ├── assistant_tool_choice_function.py
│       │   │   ├── assistant_tool_choice_function_param.py
│       │   │   ├── assistant_tool_choice_option.py
│       │   │   ├── assistant_tool_choice_option_param.py
│       │   │   ├── assistant_tool_choice_param.py
│       │   │   ├── assistant_tool_param.py
│       │   │   ├── assistant_update_params.py
│       │   │   ├── chat
│       │   │   │   └── __init__.py
│       │   │   ├── code_interpreter_tool.py
│       │   │   ├── code_interpreter_tool_param.py
│       │   │   ├── file_search_tool.py
│       │   │   ├── file_search_tool_param.py
│       │   │   ├── function_tool.py
│       │   │   ├── function_tool_param.py
│       │   │   ├── realtime
│       │   │   │   ├── __init__.py
│       │   │   │   ├── conversation_created_event.py
│       │   │   │   ├── conversation_item.py
│       │   │   │   ├── conversation_item_content.py
│       │   │   │   ├── conversation_item_content_param.py
│       │   │   │   ├── conversation_item_create_event.py
│       │   │   │   ├── conversation_item_create_event_param.py
│       │   │   │   ├── conversation_item_created_event.py
│       │   │   │   ├── conversation_item_delete_event.py
│       │   │   │   ├── conversation_item_delete_event_param.py
│       │   │   │   ├── conversation_item_deleted_event.py
│       │   │   │   ├── conversation_item_input_audio_transcription_completed_event.py
│       │   │   │   ├── conversation_item_input_audio_transcription_delta_event.py
│       │   │   │   ├── conversation_item_input_audio_transcription_failed_event.py
│       │   │   │   ├── conversation_item_param.py
│       │   │   │   ├── conversation_item_retrieve_event.py
│       │   │   │   ├── conversation_item_retrieve_event_param.py
│       │   │   │   ├── conversation_item_truncate_event.py
│       │   │   │   ├── conversation_item_truncate_event_param.py
│       │   │   │   ├── conversation_item_truncated_event.py
│       │   │   │   ├── conversation_item_with_reference.py
│       │   │   │   ├── conversation_item_with_reference_param.py
│       │   │   │   ├── error_event.py
│       │   │   │   ├── input_audio_buffer_append_event.py
│       │   │   │   ├── input_audio_buffer_append_event_param.py
│       │   │   │   ├── input_audio_buffer_clear_event.py
│       │   │   │   ├── input_audio_buffer_clear_event_param.py
│       │   │   │   ├── input_audio_buffer_cleared_event.py
│       │   │   │   ├── input_audio_buffer_commit_event.py
│       │   │   │   ├── input_audio_buffer_commit_event_param.py
│       │   │   │   ├── input_audio_buffer_committed_event.py
│       │   │   │   ├── input_audio_buffer_speech_started_event.py
│       │   │   │   ├── input_audio_buffer_speech_stopped_event.py
│       │   │   │   ├── rate_limits_updated_event.py
│       │   │   │   ├── realtime_client_event.py
│       │   │   │   ├── realtime_client_event_param.py
│       │   │   │   ├── realtime_connect_params.py
│       │   │   │   ├── realtime_response.py
│       │   │   │   ├── realtime_response_status.py
│       │   │   │   ├── realtime_response_usage.py
│       │   │   │   ├── realtime_server_event.py
│       │   │   │   ├── response_audio_delta_event.py
│       │   │   │   ├── response_audio_done_event.py
│       │   │   │   ├── response_audio_transcript_delta_event.py
│       │   │   │   ├── response_audio_transcript_done_event.py
│       │   │   │   ├── response_cancel_event.py
│       │   │   │   ├── response_cancel_event_param.py
│       │   │   │   ├── response_content_part_added_event.py
│       │   │   │   ├── response_content_part_done_event.py
│       │   │   │   ├── response_create_event.py
│       │   │   │   ├── response_create_event_param.py
│       │   │   │   ├── response_created_event.py
│       │   │   │   ├── response_done_event.py
│       │   │   │   ├── response_function_call_arguments_delta_event.py
│       │   │   │   ├── response_function_call_arguments_done_event.py
│       │   │   │   ├── response_output_item_added_event.py
│       │   │   │   ├── response_output_item_done_event.py
│       │   │   │   ├── response_text_delta_event.py
│       │   │   │   ├── response_text_done_event.py
│       │   │   │   ├── session.py
│       │   │   │   ├── session_create_params.py
│       │   │   │   ├── session_create_response.py
│       │   │   │   ├── session_created_event.py
│       │   │   │   ├── session_update_event.py
│       │   │   │   ├── session_update_event_param.py
│       │   │   │   ├── session_updated_event.py
│       │   │   │   ├── transcription_session.py
│       │   │   │   ├── transcription_session_create_params.py
│       │   │   │   ├── transcription_session_update.py
│       │   │   │   ├── transcription_session_update_param.py
│       │   │   │   └── transcription_session_updated_event.py
│       │   │   ├── thread.py
│       │   │   ├── thread_create_and_run_params.py
│       │   │   ├── thread_create_params.py
│       │   │   ├── thread_deleted.py
│       │   │   ├── thread_update_params.py
│       │   │   └── threads
│       │   │       ├── __init__.py
│       │   │       ├── annotation.py
│       │   │       ├── annotation_delta.py
│       │   │       ├── file_citation_annotation.py
│       │   │       ├── file_citation_delta_annotation.py
│       │   │       ├── file_path_annotation.py
│       │   │       ├── file_path_delta_annotation.py
│       │   │       ├── image_file.py
│       │   │       ├── image_file_content_block.py
│       │   │       ├── image_file_content_block_param.py
│       │   │       ├── image_file_delta.py
│       │   │       ├── image_file_delta_block.py
│       │   │       ├── image_file_param.py
│       │   │       ├── image_url.py
│       │   │       ├── image_url_content_block.py
│       │   │       ├── image_url_content_block_param.py
│       │   │       ├── image_url_delta.py
│       │   │       ├── image_url_delta_block.py
│       │   │       ├── image_url_param.py
│       │   │       ├── message.py
│       │   │       ├── message_content.py
│       │   │       ├── message_content_delta.py
│       │   │       ├── message_content_part_param.py
│       │   │       ├── message_create_params.py
│       │   │       ├── message_deleted.py
│       │   │       ├── message_delta.py
│       │   │       ├── message_delta_event.py
│       │   │       ├── message_list_params.py
│       │   │       ├── message_update_params.py
│       │   │       ├── refusal_content_block.py
│       │   │       ├── refusal_delta_block.py
│       │   │       ├── required_action_function_tool_call.py
│       │   │       ├── run.py
│       │   │       ├── run_create_params.py
│       │   │       ├── run_list_params.py
│       │   │       ├── run_status.py
│       │   │       ├── run_submit_tool_outputs_params.py
│       │   │       ├── run_update_params.py
│       │   │       ├── runs
│       │   │       │   ├── __init__.py
│       │   │       │   ├── code_interpreter_logs.py
│       │   │       │   ├── code_interpreter_output_image.py
│       │   │       │   ├── code_interpreter_tool_call.py
│       │   │       │   ├── code_interpreter_tool_call_delta.py
│       │   │       │   ├── file_search_tool_call.py
│       │   │       │   ├── file_search_tool_call_delta.py
│       │   │       │   ├── function_tool_call.py
│       │   │       │   ├── function_tool_call_delta.py
│       │   │       │   ├── message_creation_step_details.py
│       │   │       │   ├── run_step.py
│       │   │       │   ├── run_step_delta.py
│       │   │       │   ├── run_step_delta_event.py
│       │   │       │   ├── run_step_delta_message_delta.py
│       │   │       │   ├── run_step_include.py
│       │   │       │   ├── step_list_params.py
│       │   │       │   ├── step_retrieve_params.py
│       │   │       │   ├── tool_call.py
│       │   │       │   ├── tool_call_delta.py
│       │   │       │   ├── tool_call_delta_object.py
│       │   │       │   └── tool_calls_step_details.py
│       │   │       ├── text.py
│       │   │       ├── text_content_block.py
│       │   │       ├── text_content_block_param.py
│       │   │       ├── text_delta.py
│       │   │       └── text_delta_block.py
│       │   ├── chat
│       │   │   ├── __init__.py
│       │   │   ├── chat_completion.py
│       │   │   ├── chat_completion_allowed_tool_choice_param.py
│       │   │   ├── chat_completion_allowed_tools_param.py
│       │   │   ├── chat_completion_assistant_message_param.py
│       │   │   ├── chat_completion_audio.py
│       │   │   ├── chat_completion_audio_param.py
│       │   │   ├── chat_completion_chunk.py
│       │   │   ├── chat_completion_content_part_image.py
│       │   │   ├── chat_completion_content_part_image_param.py
│       │   │   ├── chat_completion_content_part_input_audio_param.py
│       │   │   ├── chat_completion_content_part_param.py
│       │   │   ├── chat_completion_content_part_refusal_param.py
│       │   │   ├── chat_completion_content_part_text.py
│       │   │   ├── chat_completion_content_part_text_param.py
│       │   │   ├── chat_completion_custom_tool_param.py
│       │   │   ├── chat_completion_deleted.py
│       │   │   ├── chat_completion_developer_message_param.py
│       │   │   ├── chat_completion_function_call_option_param.py
│       │   │   ├── chat_completion_function_message_param.py
│       │   │   ├── chat_completion_function_tool.py
│       │   │   ├── chat_completion_function_tool_param.py
│       │   │   ├── chat_completion_message.py
│       │   │   ├── chat_completion_message_custom_tool_call.py
│       │   │   ├── chat_completion_message_custom_tool_call_param.py
│       │   │   ├── chat_completion_message_function_tool_call.py
│       │   │   ├── chat_completion_message_function_tool_call_param.py
│       │   │   ├── chat_completion_message_param.py
│       │   │   ├── chat_completion_message_tool_call.py
│       │   │   ├── chat_completion_message_tool_call_param.py
│       │   │   ├── chat_completion_message_tool_call_union_param.py
│       │   │   ├── chat_completion_modality.py
│       │   │   ├── chat_completion_named_tool_choice_custom_param.py
│       │   │   ├── chat_completion_named_tool_choice_param.py
│       │   │   ├── chat_completion_prediction_content_param.py
│       │   │   ├── chat_completion_reasoning_effort.py
│       │   │   ├── chat_completion_role.py
│       │   │   ├── chat_completion_store_message.py
│       │   │   ├── chat_completion_stream_options_param.py
│       │   │   ├── chat_completion_system_message_param.py
│       │   │   ├── chat_completion_token_logprob.py
│       │   │   ├── chat_completion_tool_choice_option_param.py
│       │   │   ├── chat_completion_tool_message_param.py
│       │   │   ├── chat_completion_tool_param.py
│       │   │   ├── chat_completion_tool_union_param.py
│       │   │   ├── chat_completion_user_message_param.py
│       │   │   ├── completion_create_params.py
│       │   │   ├── completion_list_params.py
│       │   │   ├── completion_update_params.py
│       │   │   ├── completions
│       │   │   │   ├── __init__.py
│       │   │   │   └── message_list_params.py
│       │   │   ├── parsed_chat_completion.py
│       │   │   └── parsed_function_tool_call.py
│       │   ├── chat_model.py
│       │   ├── completion.py
│       │   ├── completion_choice.py
│       │   ├── completion_create_params.py
│       │   ├── completion_usage.py
│       │   ├── container_create_params.py
│       │   ├── container_create_response.py
│       │   ├── container_list_params.py
│       │   ├── container_list_response.py
│       │   ├── container_retrieve_response.py
│       │   ├── containers
│       │   │   ├── __init__.py
│       │   │   ├── file_create_params.py
│       │   │   ├── file_create_response.py
│       │   │   ├── file_list_params.py
│       │   │   ├── file_list_response.py
│       │   │   ├── file_retrieve_response.py
│       │   │   └── files
│       │   │       └── __init__.py
│       │   ├── conversations
│       │   │   ├── __init__.py
│       │   │   ├── computer_screenshot_content.py
│       │   │   ├── container_file_citation_body.py
│       │   │   ├── conversation.py
│       │   │   ├── conversation_create_params.py
│       │   │   ├── conversation_deleted_resource.py
│       │   │   ├── conversation_item.py
│       │   │   ├── conversation_item_list.py
│       │   │   ├── conversation_update_params.py
│       │   │   ├── file_citation_body.py
│       │   │   ├── input_file_content.py
│       │   │   ├── input_image_content.py
│       │   │   ├── input_text_content.py
│       │   │   ├── item_create_params.py
│       │   │   ├── item_list_params.py
│       │   │   ├── item_retrieve_params.py
│       │   │   ├── lob_prob.py
│       │   │   ├── message.py
│       │   │   ├── output_text_content.py
│       │   │   ├── refusal_content.py
│       │   │   ├── summary_text_content.py
│       │   │   ├── text_content.py
│       │   │   ├── top_log_prob.py
│       │   │   └── url_citation_body.py
│       │   ├── create_embedding_response.py
│       │   ├── embedding.py
│       │   ├── embedding_create_params.py
│       │   ├── embedding_model.py
│       │   ├── eval_create_params.py
│       │   ├── eval_create_response.py
│       │   ├── eval_custom_data_source_config.py
│       │   ├── eval_delete_response.py
│       │   ├── eval_list_params.py
│       │   ├── eval_list_response.py
│       │   ├── eval_retrieve_response.py
│       │   ├── eval_stored_completions_data_source_config.py
│       │   ├── eval_update_params.py
│       │   ├── eval_update_response.py
│       │   ├── evals
│       │   │   ├── __init__.py
│       │   │   ├── create_eval_completions_run_data_source.py
│       │   │   ├── create_eval_completions_run_data_source_param.py
│       │   │   ├── create_eval_jsonl_run_data_source.py
│       │   │   ├── create_eval_jsonl_run_data_source_param.py
│       │   │   ├── eval_api_error.py
│       │   │   ├── run_cancel_response.py
│       │   │   ├── run_create_params.py
│       │   │   ├── run_create_response.py
│       │   │   ├── run_delete_response.py
│       │   │   ├── run_list_params.py
│       │   │   ├── run_list_response.py
│       │   │   ├── run_retrieve_response.py
│       │   │   └── runs
│       │   │       ├── __init__.py
│       │   │       ├── output_item_list_params.py
│       │   │       ├── output_item_list_response.py
│       │   │       └── output_item_retrieve_response.py
│       │   ├── file_chunking_strategy.py
│       │   ├── file_chunking_strategy_param.py
│       │   ├── file_content.py
│       │   ├── file_create_params.py
│       │   ├── file_deleted.py
│       │   ├── file_list_params.py
│       │   ├── file_object.py
│       │   ├── file_purpose.py
│       │   ├── fine_tuning
│       │   │   ├── __init__.py
│       │   │   ├── alpha
│       │   │   │   ├── __init__.py
│       │   │   │   ├── grader_run_params.py
│       │   │   │   ├── grader_run_response.py
│       │   │   │   ├── grader_validate_params.py
│       │   │   │   └── grader_validate_response.py
│       │   │   ├── checkpoints
│       │   │   │   ├── __init__.py
│       │   │   │   ├── permission_create_params.py
│       │   │   │   ├── permission_create_response.py
│       │   │   │   ├── permission_delete_response.py
│       │   │   │   ├── permission_retrieve_params.py
│       │   │   │   └── permission_retrieve_response.py
│       │   │   ├── dpo_hyperparameters.py
│       │   │   ├── dpo_hyperparameters_param.py
│       │   │   ├── dpo_method.py
│       │   │   ├── dpo_method_param.py
│       │   │   ├── fine_tuning_job.py
│       │   │   ├── fine_tuning_job_event.py
│       │   │   ├── fine_tuning_job_integration.py
│       │   │   ├── fine_tuning_job_wandb_integration.py
│       │   │   ├── fine_tuning_job_wandb_integration_object.py
│       │   │   ├── job_create_params.py
│       │   │   ├── job_list_events_params.py
│       │   │   ├── job_list_params.py
│       │   │   ├── jobs
│       │   │   │   ├── __init__.py
│       │   │   │   ├── checkpoint_list_params.py
│       │   │   │   └── fine_tuning_job_checkpoint.py
│       │   │   ├── reinforcement_hyperparameters.py
│       │   │   ├── reinforcement_hyperparameters_param.py
│       │   │   ├── reinforcement_method.py
│       │   │   ├── reinforcement_method_param.py
│       │   │   ├── supervised_hyperparameters.py
│       │   │   ├── supervised_hyperparameters_param.py
│       │   │   ├── supervised_method.py
│       │   │   └── supervised_method_param.py
│       │   ├── graders
│       │   │   ├── __init__.py
│       │   │   ├── label_model_grader.py
│       │   │   ├── label_model_grader_param.py
│       │   │   ├── multi_grader.py
│       │   │   ├── multi_grader_param.py
│       │   │   ├── python_grader.py
│       │   │   ├── python_grader_param.py
│       │   │   ├── score_model_grader.py
│       │   │   ├── score_model_grader_param.py
│       │   │   ├── string_check_grader.py
│       │   │   ├── string_check_grader_param.py
│       │   │   ├── text_similarity_grader.py
│       │   │   └── text_similarity_grader_param.py
│       │   ├── image.py
│       │   ├── image_create_variation_params.py
│       │   ├── image_edit_completed_event.py
│       │   ├── image_edit_params.py
│       │   ├── image_edit_partial_image_event.py
│       │   ├── image_edit_stream_event.py
│       │   ├── image_gen_completed_event.py
│       │   ├── image_gen_partial_image_event.py
│       │   ├── image_gen_stream_event.py
│       │   ├── image_generate_params.py
│       │   ├── image_model.py
│       │   ├── images_response.py
│       │   ├── model.py
│       │   ├── model_deleted.py
│       │   ├── moderation.py
│       │   ├── moderation_create_params.py
│       │   ├── moderation_create_response.py
│       │   ├── moderation_image_url_input_param.py
│       │   ├── moderation_model.py
│       │   ├── moderation_multi_modal_input_param.py
│       │   ├── moderation_text_input_param.py
│       │   ├── other_file_chunking_strategy_object.py
│       │   ├── responses
│       │   │   ├── __init__.py
│       │   │   ├── computer_tool.py
│       │   │   ├── computer_tool_param.py
│       │   │   ├── custom_tool.py
│       │   │   ├── custom_tool_param.py
│       │   │   ├── easy_input_message.py
│       │   │   ├── easy_input_message_param.py
│       │   │   ├── file_search_tool.py
│       │   │   ├── file_search_tool_param.py
│       │   │   ├── function_tool.py
│       │   │   ├── function_tool_param.py
│       │   │   ├── input_item_list_params.py
│       │   │   ├── parsed_response.py
│       │   │   ├── response.py
│       │   │   ├── response_audio_delta_event.py
│       │   │   ├── response_audio_done_event.py
│       │   │   ├── response_audio_transcript_delta_event.py
│       │   │   ├── response_audio_transcript_done_event.py
│       │   │   ├── response_code_interpreter_call_code_delta_event.py
│       │   │   ├── response_code_interpreter_call_code_done_event.py
│       │   │   ├── response_code_interpreter_call_completed_event.py
│       │   │   ├── response_code_interpreter_call_in_progress_event.py
│       │   │   ├── response_code_interpreter_call_interpreting_event.py
│       │   │   ├── response_code_interpreter_tool_call.py
│       │   │   ├── response_code_interpreter_tool_call_param.py
│       │   │   ├── response_completed_event.py
│       │   │   ├── response_computer_tool_call.py
│       │   │   ├── response_computer_tool_call_output_item.py
│       │   │   ├── response_computer_tool_call_output_screenshot.py
│       │   │   ├── response_computer_tool_call_output_screenshot_param.py
│       │   │   ├── response_computer_tool_call_param.py
│       │   │   ├── response_content_part_added_event.py
│       │   │   ├── response_content_part_done_event.py
│       │   │   ├── response_conversation_param.py
│       │   │   ├── response_create_params.py
│       │   │   ├── response_created_event.py
│       │   │   ├── response_custom_tool_call.py
│       │   │   ├── response_custom_tool_call_input_delta_event.py
│       │   │   ├── response_custom_tool_call_input_done_event.py
│       │   │   ├── response_custom_tool_call_output.py
│       │   │   ├── response_custom_tool_call_output_param.py
│       │   │   ├── response_custom_tool_call_param.py
│       │   │   ├── response_error.py
│       │   │   ├── response_error_event.py
│       │   │   ├── response_failed_event.py
│       │   │   ├── response_file_search_call_completed_event.py
│       │   │   ├── response_file_search_call_in_progress_event.py
│       │   │   ├── response_file_search_call_searching_event.py
│       │   │   ├── response_file_search_tool_call.py
│       │   │   ├── response_file_search_tool_call_param.py
│       │   │   ├── response_format_text_config.py
│       │   │   ├── response_format_text_config_param.py
│       │   │   ├── response_format_text_json_schema_config.py
│       │   │   ├── response_format_text_json_schema_config_param.py
│       │   │   ├── response_function_call_arguments_delta_event.py
│       │   │   ├── response_function_call_arguments_done_event.py
│       │   │   ├── response_function_tool_call.py
│       │   │   ├── response_function_tool_call_item.py
│       │   │   ├── response_function_tool_call_output_item.py
│       │   │   ├── response_function_tool_call_param.py
│       │   │   ├── response_function_web_search.py
│       │   │   ├── response_function_web_search_param.py
│       │   │   ├── response_image_gen_call_completed_event.py
│       │   │   ├── response_image_gen_call_generating_event.py
│       │   │   ├── response_image_gen_call_in_progress_event.py
│       │   │   ├── response_image_gen_call_partial_image_event.py
│       │   │   ├── response_in_progress_event.py
│       │   │   ├── response_includable.py
│       │   │   ├── response_incomplete_event.py
│       │   │   ├── response_input_content.py
│       │   │   ├── response_input_content_param.py
│       │   │   ├── response_input_file.py
│       │   │   ├── response_input_file_param.py
│       │   │   ├── response_input_image.py
│       │   │   ├── response_input_image_param.py
│       │   │   ├── response_input_item.py
│       │   │   ├── response_input_item_param.py
│       │   │   ├── response_input_message_content_list.py
│       │   │   ├── response_input_message_content_list_param.py
│       │   │   ├── response_input_message_item.py
│       │   │   ├── response_input_param.py
│       │   │   ├── response_input_text.py
│       │   │   ├── response_input_text_param.py
│       │   │   ├── response_item.py
│       │   │   ├── response_item_list.py
│       │   │   ├── response_mcp_call_arguments_delta_event.py
│       │   │   ├── response_mcp_call_arguments_done_event.py
│       │   │   ├── response_mcp_call_completed_event.py
│       │   │   ├── response_mcp_call_failed_event.py
│       │   │   ├── response_mcp_call_in_progress_event.py
│       │   │   ├── response_mcp_list_tools_completed_event.py
│       │   │   ├── response_mcp_list_tools_failed_event.py
│       │   │   ├── response_mcp_list_tools_in_progress_event.py
│       │   │   ├── response_output_item.py
│       │   │   ├── response_output_item_added_event.py
│       │   │   ├── response_output_item_done_event.py
│       │   │   ├── response_output_message.py
│       │   │   ├── response_output_message_param.py
│       │   │   ├── response_output_refusal.py
│       │   │   ├── response_output_refusal_param.py
│       │   │   ├── response_output_text.py
│       │   │   ├── response_output_text_annotation_added_event.py
│       │   │   ├── response_output_text_param.py
│       │   │   ├── response_prompt.py
│       │   │   ├── response_prompt_param.py
│       │   │   ├── response_queued_event.py
│       │   │   ├── response_reasoning_item.py
│       │   │   ├── response_reasoning_item_param.py
│       │   │   ├── response_reasoning_summary_part_added_event.py
│       │   │   ├── response_reasoning_summary_part_done_event.py
│       │   │   ├── response_reasoning_summary_text_delta_event.py
│       │   │   ├── response_reasoning_summary_text_done_event.py
│       │   │   ├── response_reasoning_text_delta_event.py
│       │   │   ├── response_reasoning_text_done_event.py
│       │   │   ├── response_refusal_delta_event.py
│       │   │   ├── response_refusal_done_event.py
│       │   │   ├── response_retrieve_params.py
│       │   │   ├── response_status.py
│       │   │   ├── response_stream_event.py
│       │   │   ├── response_text_config.py
│       │   │   ├── response_text_config_param.py
│       │   │   ├── response_text_delta_event.py
│       │   │   ├── response_text_done_event.py
│       │   │   ├── response_usage.py
│       │   │   ├── response_web_search_call_completed_event.py
│       │   │   ├── response_web_search_call_in_progress_event.py
│       │   │   ├── response_web_search_call_searching_event.py
│       │   │   ├── tool.py
│       │   │   ├── tool_choice_allowed.py
│       │   │   ├── tool_choice_allowed_param.py
│       │   │   ├── tool_choice_custom.py
│       │   │   ├── tool_choice_custom_param.py
│       │   │   ├── tool_choice_function.py
│       │   │   ├── tool_choice_function_param.py
│       │   │   ├── tool_choice_mcp.py
│       │   │   ├── tool_choice_mcp_param.py
│       │   │   ├── tool_choice_options.py
│       │   │   ├── tool_choice_types.py
│       │   │   ├── tool_choice_types_param.py
│       │   │   ├── tool_param.py
│       │   │   ├── web_search_tool.py
│       │   │   └── web_search_tool_param.py
│       │   ├── shared
│       │   │   ├── __init__.py
│       │   │   ├── all_models.py
│       │   │   ├── chat_model.py
│       │   │   ├── comparison_filter.py
│       │   │   ├── compound_filter.py
│       │   │   ├── custom_tool_input_format.py
│       │   │   ├── error_object.py
│       │   │   ├── function_definition.py
│       │   │   ├── function_parameters.py
│       │   │   ├── metadata.py
│       │   │   ├── reasoning.py
│       │   │   ├── reasoning_effort.py
│       │   │   ├── response_format_json_object.py
│       │   │   ├── response_format_json_schema.py
│       │   │   ├── response_format_text.py
│       │   │   ├── response_format_text_grammar.py
│       │   │   ├── response_format_text_python.py
│       │   │   └── responses_model.py
│       │   ├── shared_params
│       │   │   ├── __init__.py
│       │   │   ├── chat_model.py
│       │   │   ├── comparison_filter.py
│       │   │   ├── compound_filter.py
│       │   │   ├── custom_tool_input_format.py
│       │   │   ├── function_definition.py
│       │   │   ├── function_parameters.py
│       │   │   ├── metadata.py
│       │   │   ├── reasoning.py
│       │   │   ├── reasoning_effort.py
│       │   │   ├── response_format_json_object.py
│       │   │   ├── response_format_json_schema.py
│       │   │   ├── response_format_text.py
│       │   │   └── responses_model.py
│       │   ├── static_file_chunking_strategy.py
│       │   ├── static_file_chunking_strategy_object.py
│       │   ├── static_file_chunking_strategy_object_param.py
│       │   ├── static_file_chunking_strategy_param.py
│       │   ├── upload.py
│       │   ├── upload_complete_params.py
│       │   ├── upload_create_params.py
│       │   ├── uploads
│       │   │   ├── __init__.py
│       │   │   ├── part_create_params.py
│       │   │   └── upload_part.py
│       │   ├── vector_store.py
│       │   ├── vector_store_create_params.py
│       │   ├── vector_store_deleted.py
│       │   ├── vector_store_list_params.py
│       │   ├── vector_store_search_params.py
│       │   ├── vector_store_search_response.py
│       │   ├── vector_store_update_params.py
│       │   ├── vector_stores
│       │   │   ├── __init__.py
│       │   │   ├── file_batch_create_params.py
│       │   │   ├── file_batch_list_files_params.py
│       │   │   ├── file_content_response.py
│       │   │   ├── file_create_params.py
│       │   │   ├── file_list_params.py
│       │   │   ├── file_update_params.py
│       │   │   ├── vector_store_file.py
│       │   │   ├── vector_store_file_batch.py
│       │   │   └── vector_store_file_deleted.py
│       │   ├── webhooks
│       │   │   ├── __init__.py
│       │   │   ├── batch_cancelled_webhook_event.py
│       │   │   ├── batch_completed_webhook_event.py
│       │   │   ├── batch_expired_webhook_event.py
│       │   │   ├── batch_failed_webhook_event.py
│       │   │   ├── eval_run_canceled_webhook_event.py
│       │   │   ├── eval_run_failed_webhook_event.py
│       │   │   ├── eval_run_succeeded_webhook_event.py
│       │   │   ├── fine_tuning_job_cancelled_webhook_event.py
│       │   │   ├── fine_tuning_job_failed_webhook_event.py
│       │   │   ├── fine_tuning_job_succeeded_webhook_event.py
│       │   │   ├── response_cancelled_webhook_event.py
│       │   │   ├── response_completed_webhook_event.py
│       │   │   ├── response_failed_webhook_event.py
│       │   │   ├── response_incomplete_webhook_event.py
│       │   │   └── unwrap_webhook_event.py
│       │   └── websocket_connection_options.py
│       └── version.py
├── tests
│   ├── __init__.py
│   ├── api_resources
│   │   ├── __init__.py
│   │   ├── audio
│   │   │   ├── __init__.py
│   │   │   ├── test_speech.py
│   │   │   ├── test_transcriptions.py
│   │   │   └── test_translations.py
│   │   ├── beta
│   │   │   ├── __init__.py
│   │   │   ├── realtime
│   │   │   │   ├── __init__.py
│   │   │   │   ├── test_sessions.py
│   │   │   │   └── test_transcription_sessions.py
│   │   │   ├── test_assistants.py
│   │   │   ├── test_realtime.py
│   │   │   ├── test_threads.py
│   │   │   └── threads
│   │   │       ├── __init__.py
│   │   │       ├── runs
│   │   │       │   ├── __init__.py
│   │   │       │   └── test_steps.py
│   │   │       ├── test_messages.py
│   │   │       └── test_runs.py
│   │   ├── chat
│   │   │   ├── __init__.py
│   │   │   ├── completions
│   │   │   │   ├── __init__.py
│   │   │   │   └── test_messages.py
│   │   │   └── test_completions.py
│   │   ├── containers
│   │   │   ├── __init__.py
│   │   │   ├── files
│   │   │   │   ├── __init__.py
│   │   │   │   └── test_content.py
│   │   │   └── test_files.py
│   │   ├── conversations
│   │   │   ├── __init__.py
│   │   │   └── test_items.py
│   │   ├── evals
│   │   │   ├── __init__.py
│   │   │   ├── runs
│   │   │   │   ├── __init__.py
│   │   │   │   └── test_output_items.py
│   │   │   └── test_runs.py
│   │   ├── fine_tuning
│   │   │   ├── __init__.py
│   │   │   ├── alpha
│   │   │   │   ├── __init__.py
│   │   │   │   └── test_graders.py
│   │   │   ├── checkpoints
│   │   │   │   ├── __init__.py
│   │   │   │   └── test_permissions.py
│   │   │   ├── jobs
│   │   │   │   ├── __init__.py
│   │   │   │   └── test_checkpoints.py
│   │   │   └── test_jobs.py
│   │   ├── responses
│   │   │   ├── __init__.py
│   │   │   └── test_input_items.py
│   │   ├── test_batches.py
│   │   ├── test_completions.py
│   │   ├── test_containers.py
│   │   ├── test_conversations.py
│   │   ├── test_embeddings.py
│   │   ├── test_evals.py
│   │   ├── test_files.py
│   │   ├── test_images.py
│   │   ├── test_models.py
│   │   ├── test_moderations.py
│   │   ├── test_responses.py
│   │   ├── test_uploads.py
│   │   ├── test_vector_stores.py
│   │   ├── test_webhooks.py
│   │   ├── uploads
│   │   │   ├── __init__.py
│   │   │   └── test_parts.py
│   │   └── vector_stores
│   │       ├── __init__.py
│   │       ├── test_file_batches.py
│   │       └── test_files.py
│   ├── compat
│   │   └── test_tool_param.py
│   ├── conftest.py
│   ├── lib
│   │   ├── __init__.py
│   │   ├── chat
│   │   │   ├── __init__.py
│   │   │   ├── test_completions.py
│   │   │   └── test_completions_streaming.py
│   │   ├── responses
│   │   │   ├── __init__.py
│   │   │   └── test_responses.py
│   │   ├── schema_types
│   │   │   └── query.py
│   │   ├── snapshots.py
│   │   ├── test_assistants.py
│   │   ├── test_audio.py
│   │   ├── test_azure.py
│   │   ├── test_old_api.py
│   │   ├── test_pydantic.py
│   │   └── utils.py
│   ├── sample_file.txt
│   ├── test_client.py
│   ├── test_deepcopy.py
│   ├── test_extract_files.py
│   ├── test_files.py
│   ├── test_legacy_response.py
│   ├── test_models.py
│   ├── test_module_client.py
│   ├── test_qs.py
│   ├── test_required_args.py
│   ├── test_response.py
│   ├── test_streaming.py
│   ├── test_transform.py
│   ├── test_utils
│   │   ├── test_logging.py
│   │   ├── test_proxy.py
│   │   └── test_typing.py
│   └── utils.py
└── tree.txt

94 directories, 905 files
