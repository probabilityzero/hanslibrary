---
{"dg-publish":true,"dg-path":"Lifebook/Lifebook.md","permalink":"/lifebook/lifebook/","contentClasses":"padding.css","tags":["gardenEntry"]}
---



<style scope=" ">.taskido {
	cursor: default;
	user-select: none;
}
.taskido a {
	text-decoration: none !important;
	color: inherit !important;
}
.taskido span {
	display: contents;
}
.taskido .task .innerLink,
.taskido .task .outerLink {
	color: var(--interactive-accent);
	text-decoration: underline !important;
}
.taskido .year {
	font-size: 30px;
	font-weight: bold;
	margin: 20px 0;
	color: var(--text-normal);
	text-align: center;
}
.taskido .details {
	display: flex;
	flex-direction: column;
	flex-wrap: nowrap;
	width: 100%;
	height: auto;
}
.taskido .todayHeader {
	font-size: 24px;
	font-weight: bold;
	text-align: center;
	margin: 10px 5px;
	border-radius: 10px;
	cursor: pointer;
}
.taskido .details.today {
	padding: 30px 0;
}
.taskido .counters {
	display: flex;
	flex-direction: row;
	flex-wrap: nowrap;
	justify-content: center;
	align-content: center;
	margin: 20px 0;
}
.taskido .counter {
	display: flex;
	flex-direction: column;
	flex-wrap: nowrap;
	color: var(--text-normal);
	border-radius: 10px;
	padding: 5px;
	text-align: center;
	flex: 1 1 0;
	margin: 0 5px;
	min-width: 70px;
	max-width: 150px;
	overflow: hidden;
	background: var(--interactive-normal);
	box-shadow: var(--input-shadow);
	cursor: pointer;
}
.taskido .count {
	font-size: 18px;
	font-weight: normal;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}
.taskido .counter .label {
	font-size: 12px;
	font-weight: normal;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}
.taskido .dateLine {
	display: flex;
	flex-direction: row;
	flex-wrap: nowrap;
	justify-content: space-between;
	align-items: center;
	margin: 10px 0;
}
.taskido .date {
	color: var(--text-normal);
	font-size: 16px;
	font-weight: bold;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}
.taskido .weekday {
	color: var(--text-normal);
	font-weight: normal;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
	font-size: 16px;
}
.taskido .task {
	display: flex;
	flex-direction: row;
	flex-wrap: nowrap;
	border-radius: 10px;
	padding: 0;
	margin: 0;
	cursor: pointer;
}
.taskido .timeline,
.taskido .lines {
	display: flex;
	flex-direction: column;
	flex-wrap: nowrap;
	cursor: default;
}
.taskido .timeline {
	width: 50px;
	flex-shrink: 0;
	flex-grow: 0;
}
.taskido .lines {
	flex-shrink: 1;
	flex-grow: 1;
	overflow: hidden;
}
.taskido .stripe {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-shrink: 1;
	flex-grow: 1;
	margin: 0;
}
.taskido .stripe:after {
	content: "";
	height: 100%;
	width: 0.5px;
	background: var(--checkbox-border-color);
	margin: 5px 0;
}
.taskido .task.overdue .timeline .icon svg line {
	stroke: #ff375f !important;
	stroke-width: 2.5px !important;
}
.taskido .task.done .timeline .icon svg {
	fill: var(--interactive-accent) !important;
	stroke: var(--interactive-accent) !important;
}
.taskido .task.done .timeline .icon svg path:nth-child(1) {
	fill: var(--interactive-accent) !important;
}
.taskido .task.done .timeline .icon svg path:nth-child(2) {
	stroke: var(--checkbox-marker-color) !important;
	stroke-width: 2.5px;
}
.taskido .task.done .info .tag,
.taskido .task.done .info .repeat,
.taskido .task.done .info .priority,
.taskido .task.done .info .relative,
.taskido .task.done .info .file,
.taskido .task.cancelled .info .tag,
.taskido .task.cancelled .info .repeat,
.taskido .task.cancelled .info .priority,
.taskido .task.cancelled .info .relative,
.taskido .task.cancelled .info .file {
	color: var(--text-muted) !important;
	line-height: 0;
}
.taskido .task.done .content,
.taskido .task.cancelled .content {
	text-decoration: line-through;
	color: var(--text-muted);
}
.taskido .line {
	display: flex;
	flex-direction: row;
	flex-wrap: wrap;
	align-items: center;
}
.taskido .icon {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-shrink: 0;
	flex-grow: 0;
	text-align: center;
}
.taskido .timeline .icon {
	text-align: center;
	height: 22px;
}
.taskido .timeline .icon svg {
	color: var(--checkbox-border-color);
}
.taskido .timeline .icon svg:hover {
	color: var(--checkbox-border-color-hover);
}
.taskido .timeline .icon svg {
	height: var(--checkbox-size);
	width: var(--checkbox-size);
	stroke-width: 1.75px;
}
.taskido .task .info {
	line-height: 22px;
	padding-bottom: 2px;
	cursor: default;
}
.taskido .task .info:empty {
	display: none;
}
.taskido .task .content {
	display: block;
	white-space: break-word;
	font-size: 15px;
	font-weight: normal;
	color: var(--text-normal);
	line-height: 22px;
}
.taskido .task .info .tag,
.taskido .task .info .repeat,
.taskido .task .info .priority,
.taskido .task .info .relative,
.taskido .task .info .file {
	display: flex;
	flex-direction: row;
	flex-wrap: nowrap;
	align-items: center;
	width: auto;
	font-size: 9px;
	font-weight: normal;
	margin: 2px 5px 2px 0;
	color: var(--text-muted);
	padding: 0px;
	border: none;
	line-height: 0 !important;
	padding: 0;
	border-radius: 3px !important;
}
.taskido .task .info .file {
	color: var(--task-color);
}
.taskido .task .info .tag {
	color: var(--tag-color) !important;
	cursor: pointer;
}
.taskido .info .icon {
	text-align: center;
	height: 15px;
}
.taskido .info .label {
	margin-left: 2px;
}
.taskido .info svg {
	height: 12px;
	width: 12px;
	stroke-width: 1.75px;
}
.taskido .task.overdue .info .relative {
	color: #ff375f !important;
}
/* Quick Entry Panel */
.taskido .quickEntryPanel {
	display: flex;
	flex-direction: row;
	flex-wrap: nowrap;
	background: var(--background-modifier-form-field);
	border: var(--input-border-width) solid var(--background-modifier-border);
	color: var(--text-normal);
	border-radius: 10px;
	box-shadow: 0 0 5px 0 rgba(0,0,0,0.1);
	margin: 0 5px 20px 5px;
	overflow: hidden;
	padding: 5px;
}
.taskido .quickEntryPanel .left {
	display: flex;
	flex-direction: column;
	flex-wrap: nowrap;
	align-items: center;
	width: 100%;
	flex-shrink: 1;
	flex-grow: 1;
	overflow: hidden;
	border-radius: 5px;
	padding: 0 5px !important;
}
.taskido .quickEntryPanel .right {
	display: block;
	width: auto;
	flex-shrink: 1;
	flex-grow: 1;
	overflow: hidden;
	border-radius: 5px;
}
.taskido .quickEntryPanel select,
.taskido .quickEntryPanel input,
.taskido .quickEntryPanel button {
	box-shadow: none !important;
	border: none !important;
	background: none !important;
	border-radius: 0 !important;
}
.taskido .quickEntryPanel select,
.taskido .quickEntryPanel button {
	cursor: pointer;
}
.taskido .quickEntryPanel input {
	cursor: text;
}
.taskido .quickEntryPanel select {
	height: 15px;
	width: 100%;
	font-size: 11px;
	text-overflow: ellipsis;
	white-space: nowrap;
	overflow: hidden;
	padding: 0 !important;
	margin: 2.5px 0 !important;
	color: var(--text-muted);
}
.taskido .quickEntryPanel select:hover,
.taskido .quickEntryPanel button:hover {
	color: var(--text-normal);
}
.taskido .quickEntryPanel select option,
.taskido .quickEntryPanel select optgroup {
	background: var(--background-primary);
	font-weight: normal;
	color: var(--text-normal);
}
.taskido .quickEntryPanel input {
	height: 20px;
	line-height: 20px;
	width: 100%;
	text-overflow: ellipsis;
	white-space: nowrap;
	overflow: hidden;
	padding: 0 !important;
	margin: 0 !important;
	font-size: 14px;
}
.taskido .quickEntryPanel button {
	display: flex;
	flex-direction: row;
	flex-wrap: nowrap;
	justify-content: center;
	align-items: center;
	height: 100%;
	width: auto;
	padding: 0 5px !important;
	margin: 0 !important;
	color: var(--text-muted);
}
.taskido .quickEntryPanel svg {
	height: 15px;
	width: 15px;
	stroke-width: 1.75px;
}
.taskido .quickEntryPanel select:active,
.taskido .quickEntryPanel input:active,
.taskido .quickEntryPanel button:active {
	border: none !important;
	box-shadow: none !important;
	transition: none !important;
}
/* Classes */
.taskido.todayFocus .todayHeader,
.taskido.todoFocus .counter#todo,
.taskido.todoFilter .counter#todo,
.taskido.overdueFocus .counter#overdue,
.taskido.overdueFilter .counter#overdue,
.taskido.unplannedFocus .counter#unplanned,
.taskido.unplannedFilter .counter#unplanned { color: var(--interactive-accent); background: hsla(var(--interactive-accent-hsl), 0.2); box-shadow: var(--input-shadow); }
.taskido.noYear .year,
.taskido.noRepeat .repeat,
.taskido.noTag .tag,
.taskido.noPriority .priority,
.taskido.noFile .task .file,
.taskido.noFile .task .info > .file,
.taskido.noInfo .task .line:nth-child(2),
.taskido.noDone .year[data-types="done"],
.taskido.noDone .details[data-types="done"],
.taskido.noDone .task.done,
.taskido.noUnplanned .task.unplanned,
.taskido.noUnplanned .counter#unplanned,
.taskido.noUnplanned .year[data-types="unplanned"],
.taskido.noUnplanned .details[data-types="unplanned"],
.taskido.noRelative .relative,
.taskido.noQuickEntry .quickEntryPanel,
.taskido.noCounters .counters { display: none !important; }
.taskido.noColor .task .file { color: var(--text-muted) !important }
.taskido.noColor .task .info .file { color: var(--text-muted) !important }
/* Focus */
.taskido.todayFocus .details:not(.today),
.taskido.todayFocus .year { display: none !important; }
.taskido.todayFocus .details.today { padding: 0; }
.taskido.todoFocus .details.today .task.due,
.taskido.todoFocus .details.today .task.scheduled,
.taskido.todoFocus .details.today .task.process,
.taskido.todoFocus .details.today .task.start,
.taskido.overdueFocus .task.overdue,
.taskido.unplannedFocus .task.unplanned { background: hsla(var(--interactive-accent-hsl), 0.2); }
/* Filter */
.taskido.todoFilter .year:not(.current):not([data-types*="due"][data-types*="scheduled"][data-types*="overdue"]) { display: none; }
.taskido.todoFilter .details:not(.today):not([data-types*="due"][data-types*="scheduled"][data-types*="overdue"]) { display: none; }
.taskido.todoFilter .task:not(.due, .scheduled, .process, .start) { display: none; }
.taskido.overdueFilter .year:not(.current):not([data-types*="overdue"]) { display: none; }
.taskido.overdueFilter .details:not(.today):not([data-types*="overdue"]) { display: none; }
.taskido.overdueFilter .task:not(.overdue) { display: none; }
.taskido.unplannedFilter .year:not(.current):not([data-types*="unplanned"]) { display: none; }
.taskido.unplannedFilter .details:not(.today):not([data-types*="unplanned"]) { display: none; }
.taskido.unplannedFilter .task:not(.unplanned) { display: none; }

/*# sourceURL=http://localhost/Waypoint/Utilities/Templates/Scripts/Missions/view.css */</style><div class="taskido Year noInfo todayFocus" id="taskido1749517106176"><span><div class="year" data-types="unplanned">2024</div><div class="details " data-year="2024" data-types="unplanned"><span><div class="dateLine"><div class="date">Sat, Dec 28</div><div class="weekday"></div></div><div class="content"><div aria-label="2024-12-28 &gt; LiGoal evening goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2024-12-28.md" data-col="24" data-line="134"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2024-12-28.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Power BI by *PwC*</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2024-12-28.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2024-12-28 &gt; LiGoal evening goals</div></div></div></div></div><div aria-label="2024-12-28 &gt; LiGoal evening goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2024-12-28.md" data-col="65" data-line="135"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2024-12-28.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Data Structures and Algorithms In Python lectures (give up)</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2024-12-28.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2024-12-28 &gt; LiGoal evening goals</div></div></div></div></div><div aria-label="2024-12-28 &gt; LiGoal evening goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2024-12-28.md" data-col="157" data-line="140"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2024-12-28.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">this is a note that keeps going to show how wide the text can go here as, you see it keeps on going now you can get an idea how wide we need this to be</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2024-12-28.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2024-12-28 &gt; LiGoal evening goals</div></div></div></div></div><div aria-label="2024-12-28 &gt; goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2024-12-28.md" data-col="24" data-line="178"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2024-12-28.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Power BI by *PwC*</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2024-12-28.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2024-12-28 &gt; goals</div></div></div></div></div><div aria-label="2024-12-28 &gt; goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2024-12-28.md" data-col="65" data-line="179"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2024-12-28.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Data Structures and Algorithms In Python lectures (give up)</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2024-12-28.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2024-12-28 &gt; goals</div></div></div></div></div><div aria-label="2024-12-28 &gt; goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2024-12-28.md" data-col="157" data-line="184"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2024-12-28.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">this is a note that keeps going to show how wide the text can go here as, you see it keeps on going now you can get an idea how wide we need this to be</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2024-12-28.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2024-12-28 &gt; goals</div></div></div></div></div><div aria-label="2024-12-28 &gt; goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2024-12-28.md" data-col="26" data-line="185"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2024-12-28.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">*add a new entry...*</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2024-12-28.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2024-12-28 &gt; goals</div></div></div></div></div></div></span></div><div class="year current" data-types="unplanned">2025</div><div class="details " data-year="2025" data-types="unplanned"><span><div class="dateLine"><div class="date">Fri, Jan 10</div><div class="weekday"></div></div><div class="content"><div aria-label="2025-01-10 &gt; LiGoal Morning session goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-01-10.md" data-col="22" data-line="134"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-01-10.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Chapter 11 HOML</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-01-10.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-01-10 &gt; LiGoal Morning session goals</div></div></div></div></div><div aria-label="2025-01-10 &gt; LiGoal Morning session goals" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-01-10.md" data-col="7" data-line="135"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-01-10.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">.</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-01-10.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-01-10 &gt; LiGoal Morning session goals</div></div></div></div></div></div></span></div><div class="details " data-year="2025" data-types="unplanned"><span><div class="dateLine"><div class="date">Tue, May 27</div><div class="weekday"></div></div><div class="content"><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="33" data-line="102"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Never any blocking bullshit</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="43" data-line="103"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Call me with good names to inspire me</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="34" data-line="104"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Never dare to call me badly</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="40" data-line="105"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Take care of my soul and kindle it</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="48" data-line="106"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Don't talk with me like illiterate person</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="35" data-line="107"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Never talk about other woman</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="53" data-line="108"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">VC like before, even in bath but don't show all</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="45" data-line="109"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Study with me as well, and movies etc.</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-27 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-27.md" data-col="43" data-line="111"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-27.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Your usual life update and daliya etc</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-27.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-27 &gt; Journal Entries</div></div></div></div></div></div></span></div><div class="details " data-year="2025" data-types="unplanned"><span><div class="dateLine"><div class="date">Thu, May 29</div><div class="weekday"></div></div><div class="content"><div aria-label="2025-05-29 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-29.md" data-col="44" data-line="105"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-29.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">The Age of Innocence by Edith Wharton</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-29.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-29 &gt; Journal Entries</div></div></div></div></div><div aria-label="2025-05-29 &gt; Journal Entries" style="--task-color:var(--text-muted)" class="task unplanned" data-dailynote="true" data-link="Cortex/Lifebook/2025-05-29.md" data-col="5" data-line="106"><div class="timeline"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><circle r="10" cy="12" cx="12"></circle></svg></div><div class="stripe"></div></div><div class="lines"><a href="Cortex/Lifebook/2025-05-29.md" class="internal-link" target="_blank" rel="noopener nofollow"><div class="content">Robinson Crusoe by Daniel Defoe
</div></a><div class="line info"><div aria-label="Cortex/Lifebook/2025-05-29.md" class="file"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line y2="13" x2="8" y1="13" x1="16"></line><line y2="17" x2="8" y1="17" x1="16"></line><line y2="9" x2="8" y1="9" x1="10"></line></svg></div><div class="label">2025-05-29 &gt; Journal Entries</div></div><a aria-label="#readinglist" style="--tag-color:var(--text-muted)" class="tag" href="#readinglist" target="_blank" rel="noopener nofollow"><div class="icon"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M12 2H2v10l9.29 9.29c.94.94 2.48.94 3.42 0l6.58-6.58c.94-.94.94-2.48 0-3.42L12 2Z"></path><path d="M7 7h.01"></path></svg></div><div class="label">readinglist</div></a></div></div></div></div></span></div><div class="details today" data-year="2025" data-types=""><span><div class="dateLine"><div class="date">Tue, Jun 10</div><div class="weekday"></div></div><div class="content"><div aria-label="Focus today" class="todayHeader">Today</div><div class="counters"><div aria-label="Filter tasks to do" id="todo" class="counter"><div class="count">0</div><div class="label">To Do</div></div><div aria-label="Filter overdue tasks" id="overdue" class="counter"><div class="count">0</div><div class="label">Overdue</div></div><div aria-label="Filter unplanned tasks" id="unplanned" class="counter"><div class="count">20</div><div class="label">Unplanned</div></div></div><div class="quickEntryPanel"><div class="left"><select aria-label="Select a note to add a new task to" class="fileSelect"><option value="2025-06-10.md" title="2025-06-10.md" selected="true">📄&nbsp;2025-06-10</option><option value="Cortex/Genesis/Competitive Programming Roadmap.md" title="Cortex/Genesis/Competitive Programming Roadmap.md">… / 📂&nbsp;Genesis / 📄&nbsp;Competitive Programming Roadmap</option><option value="Cortex/Genesis/Daily Meals.md" title="Cortex/Genesis/Daily Meals.md">… / 📂&nbsp;Genesis / 📄&nbsp;Daily Meals</option><option value="Cortex/Genesis/Han's Labs Services.md" title="Cortex/Genesis/Han's Labs Services.md">… / 📂&nbsp;Genesis / 📄&nbsp;Han's Labs Services</option><option value="Cortex/Genesis/Software Engineer Domains.md" title="Cortex/Genesis/Software Engineer Domains.md">… / 📂&nbsp;Genesis / 📄&nbsp;Software Engineer Domains</option><option value="Cortex/Genesis/Things I need.md" title="Cortex/Genesis/Things I need.md">… / 📂&nbsp;Genesis / 📄&nbsp;Things I need</option><option value="Cortex/Lifebook/2024-12-28.md" title="Cortex/Lifebook/2024-12-28.md">… / 📂&nbsp;Lifebook / 📄&nbsp;2024-12-28</option><option value="Cortex/Lifebook/2025-01-10.md" title="Cortex/Lifebook/2025-01-10.md">… / 📂&nbsp;Lifebook / 📄&nbsp;2025-01-10</option><option value="Cortex/Lifebook/2025-05-27.md" title="Cortex/Lifebook/2025-05-27.md">… / 📂&nbsp;Lifebook / 📄&nbsp;2025-05-27</option><option value="Cortex/Lifebook/2025-05-29.md" title="Cortex/Lifebook/2025-05-29.md">… / 📂&nbsp;Lifebook / 📄&nbsp;2025-05-29</option><option value="Cortex/Notebook/Probability Theory.md" title="Cortex/Notebook/Probability Theory.md">… / 📂&nbsp;Notebook / 📄&nbsp;Probability Theory</option><option value="Cortex/Notebook/Statistics.md" title="Cortex/Notebook/Statistics.md">… / 📂&nbsp;Notebook / 📄&nbsp;Statistics</option><option value="Eκμάδεση/Courses &amp; Specialisations/Мore Courses/See course recommendations.md" title="Eκμάδεση/Courses &amp; Specialisations/Мore Courses/See course recommendations.md">… / 📂&nbsp;Мore Courses / 📄&nbsp;See course recommendations</option><option value="Eκμάδεση/Projects &amp; Research/Projects/Portfolio &amp; Collection Platform.md" title="Eκμάδεση/Projects &amp; Research/Projects/Portfolio &amp; Collection Platform.md">… / 📂&nbsp;Projects / 📄&nbsp;Portfolio &amp; Collection Platform</option><option value="Eκμάδεση/Мore Options/Handbook/Programming and Software Tools (RAE).md" title="Eκμάδεση/Мore Options/Handbook/Programming and Software Tools (RAE).md">… / 📂&nbsp;Handbook / 📄&nbsp;Programming and Software Tools (RAE)</option><option value="Eκμάδεση/Мore Options/Handbook/Research &amp; Analysis.md" title="Eκμάδεση/Мore Options/Handbook/Research &amp; Analysis.md">… / 📂&nbsp;Handbook / 📄&nbsp;Research &amp; Analysis</option><option value="Eκμάδεση/Мore Options/Handbook/Roadmap 2024.md" title="Eκμάδεση/Мore Options/Handbook/Roadmap 2024.md">… / 📂&nbsp;Handbook / 📄&nbsp;Roadmap 2024</option><option value="Eκμάδεση/Мore Options/Handbook/linkedin profile for each.md" title="Eκμάδεση/Мore Options/Handbook/linkedin profile for each.md">… / 📂&nbsp;Handbook / 📄&nbsp;linkedin profile for each</option><option value="Library/Knowledge Glory/Knowledge Glory.md" title="Library/Knowledge Glory/Knowledge Glory.md">… / 📂&nbsp;Knowledge Glory / 📄&nbsp;Knowledge Glory</option><option value="Waypoint/Databank/People Info/Butler.md" title="Waypoint/Databank/People Info/Butler.md">… / 📂&nbsp;People Info / 📄&nbsp;Butler</option><option value="Waypoint/Domains/The Great Houses/House of El Han/Ministry of Technology &amp; Engineering/Atlas, Inc/Atlas Cloud.md" title="Waypoint/Domains/The Great Houses/House of El Han/Ministry of Technology &amp; Engineering/Atlas, Inc/Atlas Cloud.md">… / 📂&nbsp;Atlas, Inc / 📄&nbsp;Atlas Cloud</option><option value="Waypoint/Quests/BCIBF - YEAR 2.md" title="Waypoint/Quests/BCIBF - YEAR 2.md">… / 📂&nbsp;Quests / 📄&nbsp;BCIBF - YEAR 2</option><option value="Waypoint/Quests/Chronicles of Caspian.md" title="Waypoint/Quests/Chronicles of Caspian.md">… / 📂&nbsp;Quests / 📄&nbsp;Chronicles of Caspian</option><option value="Waypoint/Quests/Competitive Programming First Steps.md" title="Waypoint/Quests/Competitive Programming First Steps.md">… / 📂&nbsp;Quests / 📄&nbsp;Competitive Programming First Steps</option><option value="Waypoint/Quests/Completed Quests/BCIBF - YEAR 1.md" title="Waypoint/Quests/Completed Quests/BCIBF - YEAR 1.md">… / 📂&nbsp;Completed Quests / 📄&nbsp;BCIBF - YEAR 1</option><option value="Waypoint/Quests/Completed Quests/Whispers of Autumn's Pages.md" title="Waypoint/Quests/Completed Quests/Whispers of Autumn's Pages.md">… / 📂&nbsp;Completed Quests / 📄&nbsp;Whispers of Autumn's Pages</option><option value="Waypoint/Quests/Completed Quests/Winter's Chill.md" title="Waypoint/Quests/Completed Quests/Winter's Chill.md">… / 📂&nbsp;Completed Quests / 📄&nbsp;Winter's Chill</option><option value="Waypoint/Quests/Dorin Lambă.md" title="Waypoint/Quests/Dorin Lambă.md">… / 📂&nbsp;Quests / 📄&nbsp;Dorin Lambă</option><option value="Waypoint/Quests/Eminescu.md" title="Waypoint/Quests/Eminescu.md">… / 📂&nbsp;Quests / 📄&nbsp;Eminescu</option><option value="Waypoint/Quests/Fundstück oder.md" title="Waypoint/Quests/Fundstück oder.md">… / 📂&nbsp;Quests / 📄&nbsp;Fundstück oder</option><option value="Waypoint/Quests/Narration.md" title="Waypoint/Quests/Narration.md">… / 📂&nbsp;Quests / 📄&nbsp;Narration</option><option value="Waypoint/Quests/Springlight Solitude.md" title="Waypoint/Quests/Springlight Solitude.md">… / 📂&nbsp;Quests / 📄&nbsp;Springlight Solitude</option><option value="Waypoint/Quests/Storyteller voice.md" title="Waypoint/Quests/Storyteller voice.md">… / 📂&nbsp;Quests / 📄&nbsp;Storyteller voice</option><option value="Waypoint/Quests/Vincent Speaks.md" title="Waypoint/Quests/Vincent Speaks.md">… / 📂&nbsp;Quests / 📄&nbsp;Vincent Speaks</option><option value="Waypoint/Utilities/Templates/Reflections/Literary artistic expressions.md" title="Waypoint/Utilities/Templates/Reflections/Literary artistic expressions.md">… / 📂&nbsp;Reflections / 📄&nbsp;Literary artistic expressions</option></select><input placeholder="Enter your tasks here" type="text" class="newTask"></div><div class="right"><button aria-label="Append new task to selected note" class="ok"><svg stroke-linejoin="round" stroke-linecap="round" stroke-width="2" stroke="currentColor" fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg"><polyline points="9 10 4 15 9 20"></polyline><path d="M20 4v7a4 4 0 0 1-4 4H4"></path></svg></button></div></div></div></span></div></span></div>



# [[Library/Library\| Bookshelf]]  | [[Eκμάδεση/Projects & Research/Projects/Projects\|Projects]] |  [[Waypoint/Quests/Quests\|Quests]]  | [[Library/个人档案/个人档案\|个人档案]]


> [!example]+ Quick Access 
>  - [[Waypoint/Domains/The Great Houses/House of El Han/Ministry of Trade & Communication/New Software Standards/blackmarket.dev\|blackmarket.dev]]
> - [[Waypoint/Quests/Springlight Solitude\|Springlight Solitude]]
> - [[Library/Knowledge Glory/Knowledge Glory\|Knowledge Glory]]
> - [[Eκμάδεση/Projects & Research/Projects/Scholarly.org\|Scholarly.org]]
> - [[Cortex/Genesis/Research entities\|Research entities]]
> - [[Cortex/Genesis/Awesome quant\|Awesome quant]]
> 
{ .block-language-dataview}

